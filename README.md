# Stability Analysis using Root Locus

## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software
## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.
### Theory:
![WhatsApp Image 2025-11-27 at 23 36 59_18696c56](https://github.com/user-attachments/assets/75cf1d0a-aecf-462a-b2de-93471f46c587)
![WhatsApp Image 2025-11-27 at 23 36 57_0dffeef0](https://github.com/user-attachments/assets/8bc21d2d-5566-46ac-a018-92d7d5f0a5d9)
![WhatsApp Image 2025-11-27 at 23 36 53_7c89a38c](https://github.com/user-attachments/assets/864f500d-817f-40d6-a5bf-d01f40048fee)

![WhatsApp Image 2025-11-27 at 23 37 00_b146042b](https://github.com/user-attachments/assets/c7c19fdb-c723-4bf2-843a-287668f3bd45)




## Program:
num=[1]<br>
den=[1 15 50 0]<br>
sys=tf(num,den)<br>
rlocus(sys)<br>
[k poles]=rlocfind(sys)

## Output:
<img width="699" height="626" alt="image" src="https://github.com/user-attachments/assets/284f1cfc-5418-481c-886c-391017d8fc2b" />

## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 744.551
