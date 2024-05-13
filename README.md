# Ex04 Places Around Me
## Date:18/3/2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html
<HTML>
    <HEAD>
        <TITLE>My City</TITLE>
    </HEAD>
    <BODY>
        <h1 align="center">
            <font color="maroon"><b>Kanchipuram</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Gokul sachin k(212223220025)</b></font>
        </h3>
        <CENTER>
            <img src="map.png" usemap="#mymap" height="500" width="1000">
            <map name="mymap">
                <area title="Sri Vaikuntha Perumal Kovil" href="temple1.html" coords="652,320,880,398" shape="rect">
                <area title="A S Babu Shah" href="shop.html" coords="452,600,208" shape="circle">
                <area title="Sri Kanchi Kamakshi Amman Temple" href="temple2.html" coords="819,400,981,881" shape="rect">
                <area title="EKAMBARANATHAR TEMPLE" href="temple3.html" coords="705,315,935,337,710,414,637,317" shape="poly">
                <area title="Kaliasanathar temple" href="temple4.html" coords="422,481,119" shape="circle">
            </map>

        </CENTER>
    </BODY>
</HTML>

temple1.html
<HTML>
    <HEAD>
        <TITLE>temple1</TITLE>
    </HEAD>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="red">Kanchipuram</font>
        </h1>
        
        <h3 align="center">
            <font color="maroon">Sri Vaikuntha Perumal Kovil</font>
        </h3>
        <hr color="yellow" align="center">
        <br>
        <p><h4>
   Sri Vaikuntha Perumal Kovil is located in Kanchipuram city.This temple is one of the oldest temple located in Kanchipuram District.
  This temple stands as a testament to the rich cultural and architectural heritage of India. Dedicated to Lord Vishnu, this ancient 
  temple dates back to the Pallava dynasty, showcasing exquisite Dravidian architecture with intricate carvings and towering gopurams.
  Its sacred ambiance invites devotees to immerse themselves in devotion and spirituality. The temple's significance lies in its portrayal of Lord Vishnu in a 
  majestic reclining posture, symbolizing divine rest and eternal bliss. Sri Vaikuntha Perumal Kovil remains a revered pilgrimage site, drawing devotees from far 
  and wide to experience divine grace and tranquility.stands as a testament to the rich cultural and architectural heritage of India. Dedicated to Lord Vishnu, this
  ancient temple dates back to the Pallava dynasty, showcasing exquisite Dravidian architecture with intricate carvings and towering gopurams. Its sacred ambiance 
  invites devotees to immerse themselves in devotion and spirituality. The temple's significance lies in its portrayal of Lord Vishnu in a majestic reclining posture,
  symbolizing divine rest and eternal bliss. Sri Vaikuntha Perumal Kovil remains a revered pilgrimage site, drawing devotees from far and wide to experience divine grace and tranquility.
        </h4></p>
    </body>
</HTML>

shop.html
<HTML>
    <HEAD>
        <TITLE>shop</TITLE>
    </HEAD>
    <body bgcolor="green">
        <h1 align="center">
            <font color="orange">Kanchipuram</font>
        </h1>
        
        <h3 align="center">
            <font color="lightblue">A S BABU SHAH SHOP</font>
        </h3>
        <hr color="red" align="center">
        <br>
        <p><h4>
      A.S. Babu Shah's shop in Kanchipuram district is a renowned destination for those seeking the finest silk sarees,
    epitomizing the region's rich textile heritage. Established decades ago, the shop has garnered a reputation for its
    impeccable craftsmanship and exquisite designs. Visitors are welcomed into a world of vibrant colors and intricate motifs,
    where each saree tells a story of tradition and elegance. From classic Kanjivarams to contemporary interpretations, the shop 
  offers a diverse range to suit every taste and occasion. Beyond its role as a purveyor of luxury textiles, A.S. Babu Shah's 
shop is a cultural hub, preserving and promoting the artistry that defines Kanchipuram's silk industry.
 A.S. Babu Shah's shop in Kanchipuram district stands not only as a beacon of quality craftsmanship but
 also as a guardian of tradition. Passed down through generations, the shop has become a symbol of heritage, with each saree
 meticulously handcrafted by skilled artisans using age-old techniques. Beyond its exquisite offerings, the shop serves as a 
cultural ambassador, welcoming visitors from around the world to experience the timeless allure of Kanchipuram silk. 
        </h4></p>
    </body>
</HTML>

temple2.html
<HTML>
    <HEAD>
        <TITLE>temple2</TITLE>
    </HEAD>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="magenta">Kanchipuram</font>
        </h1>
        
        <h3 align="center">
            <font color="lightgreen">Sri Kanchi Kamakshi Amman Temple</font>
        </h3>
        <hr color="maroon" align="center">
        <br>
        <p><h4>
    The Kanchi Kamakshi Amman Temple, nestled in the sacred town of Kanchipuram, Tamil Nadu, is a revered shrine dedicated to Goddess Kamakshi, a manifestation of the divine feminine energy. Steeped in 
   mythology and history, this ancient temple is believed to date back over 2,000 years, making it one of the holiest sites in Hinduism. Its architecture, characterized by intricate carvings and 
  towering gopurams, reflects the Dravidian style and serves as a testament to the artistic brilliance of the Chola, Pallava, and Vijayanagara dynasties.
  Devotees flock to the temple to seek the blessings of Goddess Kamakshi, who is revered as the bestower of prosperity, knowledge, and marital harmony. The temple's sanctum sanctorum houses the 
 mesmerizing idol of the goddess adorned with jewels and flowers, radiating a sense of divine grace and serenity. Throughout the year, the temple hosts various festivals and rituals, further enriching 
  its spiritual ambiance and drawing pilgrims from far and wide to experience its sacred vibrations. Kanchi Kamakshi Amman Temple stands as a timeless symbol of devotion, embodying the enduring faith of 
 millions.The renowned philosopher and saint, established the temple as one of the Shakti Peethas, where Goddess Kamakshi resides as the supreme cosmic energy. This association with Adi Shankaracharya 
further elevates the temple's spiritual significance, attracting scholars and seekers of knowledge.
Moreover, the temple's surroundings are steeped in mythology, with sacred water bodies and ancient trees adding to its mystical allure. Pilgrims often participate in rituals like abhishekam (sacred 
bathing) and archana (offering prayers) to connect with the divine and seek blessings for their well-being and prosperity.
        </h4></p>
    </body>
</HTML>

temple3.html
<HTML>
    <HEAD>
        <TITLE>temple3</TITLE>
    </HEAD>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="green">Kanchipuram</font>
        </h1>
        
        <h3 align="center">
            <font color="white">EKAMBARANATHAR TEMPLE</font>
        </h3>
        <hr color="lightgreen" align="center">
        <br>
        <p><h4>
The Ekambareswarar Temple, nestled in the ancient city of Kanchipuram, Tamil Nadu, stands as a testament to the rich cultural and religious heritage of India. Dedicated to Lord Shiva, this sprawling 
 temple complex spans over 25 acres and is one of the largest temple complexes in the country. Its origins are believed to date back over 1,500 years, with contributions from various dynasties, 
including the Pallavas, Cholas, and Vijayanagara empires.One of the most striking features of the Ekambareswarar Temple is its towering gopurams (gateway towers) adorned with intricate sculptures 
 depicting mythological narratives. The temple's main sanctum houses the revered lingam, representing Lord Shiva, while the surrounding shrines are dedicated to various deities, including Kamakshi 
 Amman, the consort of Lord Shiva. The temple's sacred tank, known as the Shivaganga, adds to its spiritual ambiance, and devotees often take ritual baths here as a form of purification. Throughout 
 the year, the temple hosts numerous festivals and rituals, including the annual Panguni Uthiram festival, which attracts devotees from far and wide to witness colorful processions and religious 
ceremonies. Ekambareswarar Temple not only serves as a place of worship but also as a center for cultural preservation and spiritual enlightenment, inviting visitors to immerse themselves in its 
timeless aura of devotion and tranquility.
        </h4></p>
    </body>
</HTML>

temple4.html
<HTML>
    <HEAD>
        <TITLE>temple4</TITLE>
    </HEAD>
    <body bgcolor="lightblue">
        <h1 align="center">
            <font color="maroon">Kanchipuram</font>
        </h1>
        
        <h3 align="center">
            <font color="blueviolet">Kaliasanathar temple</font>
        </h3>
        <hr color="green" align="center">
        <br>
        <p><h4>
  The Kailasanathar Temple, nestled in the sacred town of Kanchipuram, Tamil Nadu, is a marvel of ancient Indian architecture and spirituality. Built during the Pallava dynasty in the 8th century CE, 
  it stands as one of the oldest structures in Kanchipuram and is renowned for its exquisite Dravidian style.
 Dedicated to Lord Shiva, the temple is a testimony to the artistic brilliance of the Pallava craftsmen, with its intricate carvings adorning every inch of its walls, pillars, and sanctum. The main 
 shrine houses a majestic lingam, the symbol of Lord Shiva's cosmic energy, while the surrounding complex boasts smaller shrines dedicated to various deities.
  The Kailasanathar Temple's architecture reflects a harmonious blend of spirituality and aesthetics, with its vimanas (towering structures), mandapas (pillared halls), and exquisite sculptures 
 depicting scenes from Hindu mythology. The temple's sacred tank, known as Sivaganga, adds to its serene ambiance, inviting devotees to partake in ritualistic baths for spiritual purification.
 Beyond its religious significance, the Kailasanathar Temple serves as a living heritage site, attracting historians, architects, and spiritual seekers alike. Its timeless beauty and cultural 
significance continue to inspire awe and reverence, making it a cherished landmark in India's architectural landscape and a symbol of devotion for generations to come.
       </h4></p>
    </body>
</HTML>
```
## OUTPUT
![Uploading Your paragraph text.jpg…]()

![Screenshot 2024-04-20 234820](https://github.com/Sushiendar/NearMe/assets/159266287/b0f98ad6-5c67-4559-a15f-cd8a8a128345)
![Screenshot 2024-04-20 234856](https://github.com/Sushiendar/NearMe/assets/159266287/807b4813-eeac-4a38-acdf-2b0cd3d50089)
![Screenshot 2024-04-20 235016](https://github.com/Sushiendar/NearMe/assets/159266287/a89341a5-b609-4e76-ab57-8872841869d4)
![Screenshot 2024-04-20 234754](https://github.com/Sushiendar/NearMe/assets/159266287/69772de9-7bfb-476f-81c5-92387dd835f3)
![Screenshot 2024-04-20 235322](https://github.com/Sushiendar/NearMe/assets/159266287/4410699e-bf3e-4542-ab22-b5b4d8ee08a2)

## RESULT
The program for implementing image maps using HTML is executed successfully.
