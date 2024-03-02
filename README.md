# Python-import-turtle-Advance-Art-109
Create python use import turtle graphics code
from turtle import*
title("Satyam Shorrf")
bgcolor("black")
left(90)
tracer(20)


def draw(l):
    if (l <10):
        return
    else:
        pensize(2)
        pencolor("#fff700")
        forward(l) 
        left(30) 
        draw(6*l/7)
        right(60) 
        draw(6*l/7)
        left(30)
        pensize(2)
        backward(l)
draw(60) 
right(90)
done()
