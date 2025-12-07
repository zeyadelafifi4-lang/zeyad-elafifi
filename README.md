
##zeyad mahmoud elsayed
##section:4
from tkinter import *
bot=Tk()
bot.geometry('400x500')
bot.title('home')
def fun():
    name=txt.get('1.0','end')
    lbl['text']=name
btn=Button(bot,command=fun,text='click',width='12',height='3',fg='white',bg='black',font='25')
lbl=Label(bot,width='25',height='10',fg='white',bg='black',font='25')
txt=Text(bot,width='20',height='2')
txt.pack()
btn.pack()
lbl.pack()
bot.mainloop()
