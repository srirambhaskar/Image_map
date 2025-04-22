# Ex04 Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```pyton
map.html
<html>
    <title>Mycity</title>
    <body bgcolor="white">
        <h1 align="center"><font color="black">PALLIPAT</font></h1>
        <h3 align="center">
            <font color="blue">KIRAN.MP(212224230123)</font></h3>
        <center>
            <img src="map.png"  usemap="#MyCity" height="600" width="1400">
            <map name="MyCity">
                    <area shape="rect" coords="370,280,420,320" href="Temple.html" title="SAI RAM TEMPLE">     
                    <area shape="rect" coords="770,290,830,340" href="Bank.html" title="CANARA BANK">
                    <area shape="rect" coords="400,650,550,700" href="Jewelley.html" title="SUMANGALI JEWELERY">
                    <area shape="rect" coords="1120,350,950,400" href="Nursing.html" title="VIJAY NURSING HOME">
                    <area shape="rect" coords="800,350,760,300" href="Textiles.html" title="AVP TEXTILES">
            </map>
        </center>
       

    </body>
</html>
temple.html
<html>
    <h1 align="center">
        <font face="Time New Roman" color="black" size="7">PALLIPAT</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="sky blue" size="6.5">SAI RAM TEMPLE</font>
    </h3>
    <body bgcolor="lavender" align="center">
        <hr size="4.5" color="white">
        <p align="center">
        <font face="Times New Roman" size="6">
            Sai Ram Temple is a temple dedicated to Sai Baba, a revered spiritual saint who lived in India in the late 19th and early 20th centuries. 
            Sai Baba's teachings emphasized the importance of spiritual devotion, tolerance, and the practice of love and forgivenes.
            Temples dedicated to Sai Baba can be found in various parts of the world, and they often serve as centers for prayer, meditation, and community service.
        </font>
        </p>
   </body>
</html>

textiles.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="7">PALLIPAT</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="sky blue" size="6.5">AVP TEXTILES</font>
    </h3>
    <body bgcolor="VIOLET" align="center">
        <hr size="4.5" color="white">
        <p align="center">
        <font face="Times New Roman" size="6">
            AVP Textiles is a textile manufacturing company based in India.
            They are known for producing a wide range of textiles, including fabrics, garments, and home textiles. AVP Textiles is known for its quality products and is a well-established name in the textile industry.
        </font>
        </p>
   </body>
</html>

jewellery.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color ="black" size="7">THIRUVALLUR</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="sky blue" size="6.5">JEWELLWERY</font>
    </h3>
    <body bgcolor="pink" align="center">
        <hr size="4.5" color="white">
        <p align="center">
        <font face="Times New Roman" size="6">
            Sumangali jewelry is a traditional form of jewelry worn by married women in South India, especially in states like Tamil Nadu, Andhra Pradesh, and Karnataka.
            The term "Sumangali" refers to married women who are considered auspicious and are often associated with prosperity and well-being in their family.
        </font>
        </p>
   </body>
</html>

nursing.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color ="black" size="7">THIRUVALLUR</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="sky blue" size="6.5">NURSING HOME</font>
    </h3>
    <body bgcolor="yellow" align="center">
        <hr size="4.5" color="white">
        <p align="center">
        <font face="Times New Roman" size="6">
            A nursing home, also known as a skilled nursing facility (SNF) or long-term care facility, is a residential facility that provides 24-hour nursing care to individuals who require a higher level of medical care and assistance than what can be provided at home or in an assisted living facility.
            Nursing homes are typically for elderly individuals or those with chronic or debilitating conditions who are unable to care for themselves independently.
        </font>
        </p>
   </body>
</html>

bank.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color ="black" size="7">THIRUVALLUR</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="sky blue" size="6.5">CANARA BANK</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4.5" color="white">
        <p align="center">
        <font face="Times New Roman" size="6">
            Canara Bank is one of the largest public sector banks in India, with a history dating back to 1906. 
            It was nationalized by the Government of India in 1969. Canara Bank offers a wide range of financial products and services, including retail and corporate banking, treasury operations, and investment banking.
        </font>
        </p>
   </body>
</html>
```
# OUTPUT
![Screenshot (25)](https://github.com/user-attachments/assets/c407b4b7-38f4-4f6a-abcb-675ce0d96c46)
![WhatsApp Image 2025-04-22 at 10 55 43_2d4c1ef8](https://github.com/user-attachments/assets/5caecfa3-69e4-440e-bf2e-17f5feb6f562)
![WhatsApp Image 2025-04-22 at 10 55 44_d01e7e1f](https://github.com/user-attachments/assets/f4ca5236-2580-4cbf-92f8-734f4fa451be)
![WhatsApp Image 2025-04-22 at 10 55 44_be983eab](https://github.com/user-attachments/assets/08b14a7c-8214-4a4d-9e3d-3b7811f23142)
![WhatsApp Image 2025-04-22 at 10 55 44_e384a8e0](https://github.com/user-attachments/assets/8c286a2e-d9a6-4350-96cf-b5d9e558aee2)
![WhatsApp Image 2025-04-22 at 10 55 44_26030eca](https://github.com/user-attachments/assets/71e123ea-e98d-4494-bf9a-0cecf7be5a18)

# RESULT
The program for implementing image maps using HTML is executed successfully.
