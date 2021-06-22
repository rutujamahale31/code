import java.awt.*;

import java.awt.event.*;

import java.applet.*;

/*

<applet code="health is wealth"width=400 height=300>

</applet>

public class textfield extends Applet implements Actionlistener

{

Textfield nm,age;

public void init()

{

Label nml=new Label ("name:",Label.RIGHT);

Label agel=new Label("age:",Label.RIGHT);

nm=new Textfield (30);

age=new Textfield (2);

add(nml);

add(nm);

add(agel);

add(age);

nm.addActionlistener(this);

age.addActionlistener(this);

}

public void actionPerformed(ActionEvent ae)

{

repaint();

}

public void paint(Graphics g)

{

g.drawString("name:"+nm.getText(),6,60);

g.drawString("Age:"+age.getText(),6,80);

g.drawString("Hi"+nm.getText(),"you are"+age.getText()"you should have a healthy diet plan, daily exercise and proper rest ..so that you can stay fit at the age of "+nm.getText(),6,100);

}

}
