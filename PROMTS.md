<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Assignment1</title> 

    <link rel="stylesheet" href="style.css">

</head>

<body>

    <header>

        <nav>

            <div class="logo">

                <img src="./assets/logo.png" alt="">

            </div>

            <div class="links">

                <ul> 

                    <li>Speakers</li>

                    <li>Schedule</li>

                    <li>Tracks</li>

                    <li>Venue</li>

                    <li>Blog</li>

                </ul>

            </div>

            <div class="btn">

                <button>Register Now</button>

            </div>

        </nav>

    </header>



    <main>

        <div class="hero-section">

        <h1>Code. Connect. Create</h1>

        <p>Join 4,000+ engineers, founders, and builders at the premier developer conference of 2026. Three days of cutting-edge talks, hands-on workshops, and meaningful connections.</p>

        <div class="btn"> 

            <button>Register Now</button>

        </div>

        </div>





        <div class="meet-the-speakers">

            <h1>Meet the Speakers</h1>



            <div class="card-wrapper">

                <div class="card">

                    <img src="./assets/gary.png" alt="">

                    <p class="tag">Frontend</p>

                    <h4>Gary Marcus</h4>

                    <p>Staff Engineer, Vercel</p>

                </div>





                <div class="card">

                    <img src="./assets/mustafa.png" alt="">

                    <p class="tag">Security</p>

                    <h4>Mustafa Suleyman</h4>

                    <p>CEO of Microsoft AI</p>

                </div>



                

                <div class="card">

                    <img src="./assets/demis.png" alt="">

                    <p class="tag">Cloud & DevOps</p>

                    <h4>ac Hassabis</h4>

                    <p>Co-Founder and CEO, Google DeepMind</p>

                </div>



                

                <div class="card">

                    <img src="./assets/andrej.png" alt="">

                    <p class="tag">AI / ML</p>

                    <h4>Andrej Karpathy</h4>

                    <p>Pretraining team, Anthropic</p>

                </div>

            </div>

        </div>



        <div class="payment-section">

            <h1>Secure Your Spot</h1>

            <p>Early-bird pricing ends August 15, 2026.</p>

            <div class="payment-card-wrapper">

                <div class="payment-card">

                    <p>Standard</p>

                    <h2>$399</h2>

                    <p>per person</p>

                    <ul>

                        <li>Access to all 3 conference days</li>

                        <li>48 curated technical talks</li>

                        <li>2 workshop sessions</li>

                        <li>Networking lunch & coffee breaks</li>

                        <li>Conference swag bag</li>

                        <li>Digital recordings (30 days)</li>

                    </ul>

                    <button class="payment-button-hollow">Get Standard</button>

                </div>

                <div class="payment-card-black">

                    <p>Standard</p>

                    <h2>$399</h2>

                    <p>per person</p>

                    <ul>

                        <li>Access to all 3 conference days</li>

                        <li>48 curated technical talks</li>

                        <li>2 workshop sessions</li>

                        <li>Networking lunch & coffee breaks</li>

                        <li>Conference swag bag</li>

                        <li>Digital recordings (30 days)</li>

                    </ul>

                    <button class="payment-button-hollow">Get Standard</button>

                </div>

                <div class="payment-card">

                    <p>Standard</p>

                    <h2>$399</h2>

                    <p>per person</p>

                    <ul>

                        <li>Access to all 3 conference days</li>

                        <li>48 curated technical talks</li>

                        <li>2 workshop sessions</li>

                        <li>Networking lunch & coffee breaks</li>

                        <li>Conference swag bag</li>

                        <li>Digital recordings (30 days)</li>

                    </ul>

                    <button class="payment-button-hollow">Get Standard</button>

                </div>

                

            </div>



        </div>



    </main>

</body>

</html>

this is the html 



body{

    margin: 0;

     padding: 0; 

     box-sizing: border-box;

}









nav{

    display: flex;

    align-items: center;

    justify-content: space-between;

    padding-inline: 115px;

}



.links ul{

display:flex;

gap: 15px;



}

.links ul li{

    list-style: none;

}

.btn button{

    padding-inline: 42px;

    padding-top: 12px;

    padding-bottom: 12px;

    background-color: #1D4ED8;

    color: white;

    border: none;

    border-radius: 12px;

}









.hero-section{ 

    background-image: url("./assets/banner.jpg");

  background-size: cover;

  background-position: center;

  background-repeat: no-repeat;

  height: 100vh;

  margin: 0; 

  color:white;



  display: flex;

    flex-direction: column;   

    justify-content: center;  

    align-items: center;      

    text-align: center;       



            

}



.hero-section p {

    max-width: 700px;         

}



.tag{

    color: blue;

}





.card-wrapper{

    display: grid;

    grid-template-columns: 1fr 1fr;

    gap: 30px;

}



.meet-the-speakers{

    display: grid;

    place-content: center;

    padding-top: 50px;

    padding-bottom: 50px;

    

}



.meet-the-speakers h1{

    margin-inline: auto;

}



.payment-card{

    padding: 32px;

    border: 1px solid grey;

    border-radius: 12px;



}



.payment-button-hollow{

    color: #1D4ED8;

    padding: 11px 102px;

    background: none;

    border-color: #1D4ED8;

}



.payment-card-wrapper{

    

    display: flex;

    align-items: center;

    justify-content: space-between;

}

.payment-section{

    padding: 0px 100px;



}





.payment-card-black{

    padding: 32px;

    border: 1px solid grey;

    background-color: black;

    color: white;

    border-radius: 12px;



}



this is the css



based on my coding structure build me a reletive section