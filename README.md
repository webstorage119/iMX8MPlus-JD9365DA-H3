# iMX8MPlus-JD9365DA-H3

Environment :
1. target SoC module -> https://www.iwavesystems.com/product/i-mx-8m-plus-smarc/
2. AOSP -> Android 14.0.0_2.2.0(iWave BSP)
3. GKI -> Android 15-6.6
4. Carrier Borard -> custom
5. TFT LCD Panel -> JD9365DA-H3(7 inch, 800x1280)

Screen shot :
Please check out "iMX8MPlus+JD9365DA-H3_20250904.png"

Contents :
1. panel-jadard-jd9365da-h3.c
   -> I used old type panel source code, but it's work.
      Major fixed source code part is panel initialization.
	  Also you can find a "hwang" keyword.
2. imx8mp-iwg40d-prgwd-jd9365da.dts
   -> This dts file also customized by me for our custom carrier board.

Epilogue :
I hope this source code would be help you.
