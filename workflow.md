# Title

Aim:

I want to create a desktop application which will allow me: 

- to easily write the complex math equations. 
- converting those math equations into the full latex code which will be complete equation with its caption.


Structure

1. There will be two display area in the applicaiton. left and right.
2. The left display area is for writing. We will write our equiations there. But one important thing here is that, whenever we write for example /, it automaitcally must make it fraction, when we write \ddot{x} or x'' it must automatically make it double derivative and so on. 
3. the right part will show the conversion of the left part to fully latex code. 
4. in the application top bar, there will be different buttons, for example, one button will insert the matris into the left part, and we can define the size of matris and fill its content. another example is big brackets, square brackets and so on. 


There will be copy button on the right part to copy the entire structure.

right now I want it fully functional, but after succeeding it I will turn it to fully markdown-to-latex desktop application. 

for now, just easily writeable formulas are enough. 


we can write for example: 

\formula{

caption: "My formula 1";
equation: sin(x)/cos(x)*m*p*c + arctan^2 + matrix((2,3,4), (4,5,6))

}

if it is actually easier, we can be able to write  the math part (left part) with both python code math, and visual math

is this project possible? if yes, then let's build it step by step.

firstly let's do the following

1. creating the folder with the name "Math to Latex", and create necessary folders  and files inside of it (src, gitignore, requirements.txt and so on)
2. creating the github repo with the name "math_to_latex" and conncting that repo with my local initialized repo with ssh key. 
3. then creating .venv environment using python 3.12 and installing all necessary libraries. it will be pyside6 project i thnk.
4. freezing all packages into the requirements.txt
5. excluding environment and unnecessary staff into the gitignore file.
6. pushing all necessary staff into the github repo main branch.
7. after establishing these connections, we will start to create our codes. 

i am using the terminal inside the vs code and i am using fish terminal and i have the following hardware and software 





❯ neofetch
             /////////////
         /////////////////////
      ///////*767////////////////         vasif@pop-os
    //////7676767676*//////////////       ------------
   /////76767//7676767//////////////      OS: Pop!_OS 24.04 LTS x86_64
  /////767676///*76767///////////////     Host: HP Pavilion Power Laptop 15-cb0xx
 ///////767676///76767.///7676*///////    Kernel: 7.1.5-76070105-generic
/////////767676//76767///767676////////   Uptime: 5 hours, 40 mins
//////////76767676767////76767/////////   Packages: 2095 (dpkg), 18 (flatpak)
///////////76767676//////7676//////////   Shell: fish 3.7.0
////////////,7676,///////767///////////   Resolution: 1920x1080
/////////////*7676///////76////////////   DE: COSMIC
///////////////7676////////////////////   Theme: adw-gtk3-dark [GTK3]
 ///////////////7676///767////////////    Icons: breeze-dark [GTK3]
  //////////////////////'////////////     Terminal: cosmic-term
   //////.7676767676767676767,//////      CPU: Intel i7-7700HQ (8) @ 3.800GHz
    /////767676767676767676767/////       GPU: NVIDIA GeForce GTX 1050 Mobile
      ///////////////////////////         GPU: Intel HD Graphics 630
         /////////////////////            Memory: 5017MiB / 11838MiB
         
         
         






























