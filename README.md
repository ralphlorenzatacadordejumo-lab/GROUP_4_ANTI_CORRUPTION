# GROUP_4_ANTI_CORRUPTION
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eyes Open | Anti-Corruption Advocacy</title>
    <style>

        body { font-family: 'Segoe UI', Arial, sans-serif; line-height: 1.6; margin: 0; color: #333; background: #f0f2f5; }
        
        header { background: #1a252f; color: white; padding: 100px 20px; text-align: center; }
        header h1 { font-size: 3.5rem; margin: 0; letter-spacing: 3px; }
        header p { font-size: 1.3rem; color: #bdc3c7; margin-top: 10px; }

        .container { max-width: 1100px; margin: auto; padding: 20px; }

    
        .slide { 
            background: white; 
            margin-bottom: 50px; 
            padding: 50px; 
            border-radius: 20px; 
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
            display: flex;
            flex-direction: column;
            gap: 30px }

        .slide-content { display: flex; flex-wrap: wrap; gap: 40px; align-items: center; }
        .slide-text { flex: 1; min-width: 320px; }
        .slide-image { flex: 1; min-width: 320px; }
        
        h2 { color: #c0392b; font-size: 2.2rem; border-left: 6px solid #c0392b; padding-left: 20px; margin-top: 0; }
        h3 { color: #2c3e50; font-size: 1.5rem; }
        
        img { width: 100%; border-radius: 12px; transition: transform 0.3s; }

        /* Video Container to keep 16:9 ratio */
        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            height: 0;
            overflow: hidden;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            margin-top: 20px;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
        }

        /* Help/Benefits Grid */
        .help-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 30px; }
        .help-card { background: #fffcfc; padding: 25px; border-radius: 15px; border-top: 5px solid #c0392b; box-shadow: 0 4px 6px rgba(0,0,0,0.05); }

        /* Call to Action */
        .cta-section { text-align: center; padding: 80px 20px; background: #fff; border-radius: 20px; margin-bottom: 50px; }
        .btn-action { background: #c0392b; color: white; padding: 20px 50px; text-decoration: none; border-radius: 50px; font-weight: bold; font-size: 1.2rem; display: inline-block; transition: 0.3s; }
        .btn-action:hover { background: #a93226; transform: translateY(-3px); }

        footer { text-align: center; padding: 50px; background: #1a252f; color: #bdc3c7; }
    </style>
</head>
<body>

    <header>
        <h1>EYES OPEN</h1>
        <p>Ending Corruption for a Brighter Future</p>
    </header>

    <div class="container">

        <section class="slide">
            <h2>Slide 1: The Hidden Cost</h2>
            <div class="slide-content">
                <div class="slide-text">
                    <h3>Corruption Steals Growth</h3>
                    <p>As Transparency International explains, corruption is the abuse of entrusted power for private gain. It is a theft that costs us our rights, our health, and our freedom.</p>
                    <p>Every year, we lose billions to corruption—funds that were supposed to improve our schools, hospitals, and communities.</p>
                </div>
                <div class="slide-image">
                    <img src="https://images.unsplash.com/photo-1589216532372-1c2a367900d9?q=80&w=600" alt="Scales of Justice">
                </div>
            </div>
        </section>

        <section class="slide">
            <h2>Slide 2: How We Help</h2>
            <p>Corruption is not inevitable. Together, we have the power to stop it. Here is how our advocacy makes a difference:</p>
            
            <div class="help-grid">
                <div class="help-card">
                    <h3>Transparency Training</h3>
                    <p>We educate citizens on how to monitor public funds meant for healthcare and education.</p>
                </div>
                <div class="help-card">
                    <h3>Safe Reporting</h3>
                    <p>We provide a platform to expose bribes and money laundering schemes that threaten our democracy.</p>
                </div>
                <div class="help-card">
                    <h3>Future Protection</h3>
                    <p>We fight to ensure money meant for climate crises and infrastructure isn't snatched away.</p>
                </div>
            </div>
        </section>

        <section class="slide">
            <h2>Slide 3: Watch and Learn</h2>
            <div class="slide-content">
                <div class="slide-image">
                    <img src="https://images.unsplash.com/photo-1450101499163-c8848c66ca85?q=80&w=600" alt="Documentation and Proof">
                </div>
                <div class="slide-text">
                    <h3>How Corruption Affects You</h3>
                    <p>Watch this video from Transparency International to understand how corruption erodes the rule of law and reduces your chances for a sustainable future.</p>
                    
                    <div class="video-container">
                        <iframe src="https://www.youtube.com/embed/FYorzlkCWYo" 
                                title="YouTube video player" 
                                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                                allowfullscreen>
                        </iframe>
                    </div>
                </div>
            </div>
        </section>

        <section class="cta-section">
            <h2>Be Part of the Solution</h2>
            <p>Join the movement today and help us build a more just and secure future.</p>
            <br>
            <a href="mailto:contact@eyesopen.org" class="btn-action">JOIN THE MOVEMENT</a>
        </section>

    </div>

    <footer>
        <p>&copy; 2026 Eyes Open Advocacy Alliance | Source: Transparency International</p>
    </footer>

</body>
</html>
