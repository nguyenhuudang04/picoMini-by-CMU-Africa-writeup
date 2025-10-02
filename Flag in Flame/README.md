**Flag in Flame**

Description
The SOC team discovered a suspiciously large log file after a recent breach.
When they opened it, they found an enormous block of encoded text instead of typical logs.
Could there be something hidden within? Your mission is to inspect the resulting file and reveal the real purpose of it.
The team is relying on your skills to uncover any concealed information within this unusual log.

Download the encoded data here: Logs Data. Be prepared—the file is large, and examining it thoroughly is crucial .


Hints 
Use base64 to decode the data and generate the image file.

we get the encoded log file, but the hint is base64 so we will decode it using base64

<img width="822" height="111" alt="image" src="https://github.com/user-attachments/assets/22aef3cd-b61d-4dc9-9424-55738d5d675b" />


then we check the file format and realize it is a png file
<img width="1066" height="85" alt="image" src="https://github.com/user-attachments/assets/4545b325-370c-49e1-a20e-ed140bc32cb8" />

We will convert its format to png file to view the image.

<img width="610" height="53" alt="image" src="https://github.com/user-attachments/assets/2140fdc5-67b4-4e53-b313-294d185d8a78" />

<img width="1904" height="957" alt="image" src="https://github.com/user-attachments/assets/f1be0370-e6a2-49dc-bf32-776d217b52e8" />


We will get the image with the string of characters below and then take that string of characters out.


we will decode it in hex will see the flag 
<img width="1552" height="232" alt="image" src="https://github.com/user-attachments/assets/c0e96a7c-9a72-416a-8696-d914ec9a82d8" />
