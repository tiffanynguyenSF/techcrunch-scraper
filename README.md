## 🧠 TechCrunch Scraper — AI & Startup Funding Tracker

This Colab notebook automatically scrapes **TechCrunch** news articles related to **artificial intelligence (AI)**, **startups**, and **venture funding**.  
It was developed during my **Master’s in Finance and Data Analytics** to support valuation research for **Arith Inc.**, an AI startup developing patented chip technology.

The notebook collects and analyzes TechCrunch data to identify:

- 📰 **Latest AI and tech startup news**  
- 💰 **Funding amounts and rounds** (detected from article titles containing “raises” or “raised”)  
- 📅 **Publication timelines** for market trend visualization  


### ⚙️ How It Works

**Scrapes data** from multiple TechCrunch categories:  
- [https://techcrunch.com/category/startups/](https://techcrunch.com/category/startups/)  
- [https://techcrunch.com/category/venture/](https://techcrunch.com/category/venture/)  
- [https://techcrunch.com/category/artificial-intelligence/](https://techcrunch.com/category/artificial-intelligence/)

**Extracts key fields:**
- `Title` — the article headline  
- `Date` — publication date  
- `URL` — direct article link  

**Filters** for relevant keywords such as *“raises”* and *“raised”* to focus on **funding news**.  

**Exports** all data into an Excel file (`latest_techcrunch.xlsx`) for further financial analysis or trend modeling.  

### Highlights
- **Modal** raises $25M on April 2, 2024, to train corporate workers on data and AI. [Read more](https://techcrunch.com/2024/04/02/modal-raises-25m-to-make-corporate-upskilling-more-effective/)
- The **Autism Impact Fund** closes its first $60 million fund and broadens its scope on April 2, 2024. [Read more](https://techcrunch.com/2024/04/02/autism-impact-fund/)
- **Plantee Innovations** reveals its $1.4M seed pitch deck on March 29, 2024. [Read more](https://techcrunch.com/2024/03/29/sample-seed-pitch-deck-plantee-innovations/)
- **Sam Altman** gives up control of the OpenAI Startup Fund, resolving an unusual corporate venture structure, on April 1, 2024. [Read more](https://techcrunch.com/2024/04/01/sam-altman-gives-up-control-of-openai-startup-fund-resolving-unusual-corporate-venture-structure/)
- **Skyflow** raises $30M more as AI spikes demand for its privacy business on March 28, 2024. [Read more](https://techcrunch.com/2024/03/28/skyflow-raises-30m-ai-spikes-privacy-business/)
- **Matter Venture Partners** raises its first $300M fund to invest in ‘hard tech’ on March 28, 2024. [Read more](https://techcrunch.com/2024/03/28/wen-hsieh-matter-venture-partners-300m-fund/)
- Despite challenges in the proptech sector, **Blueground** defies with $560M in revenue and a new $45M raise on March 28, 2024. [Read more](https://techcrunch.com/2024/03/28/furnished-rental-blueground-raises-45m/)
- **Satgana’s** first fund targets early-stage startups in Africa and Europe focusing on climate technology on March 28, 2024. [Read more](https://techcrunch.com/2024/03/28/satgana-closes-first-fund/)

| Title                                                                                          | Date       | URL  |
|-----------------------------------------------------------------------------------------------|------------|------|
| Modal raises $25M to train corporate workers on data and AI                                   | 2024-04-02 | [Link](https://techcrunch.com/2024/04/02/modal-raises-25m-to-make-corporate-upskilling-more-effective/)                                                  
| Quadratic is reimagining the spreadsheet with a focus on data                                | 2024-04-02 | [Link](https://techcrunch.com/2024/04/02/quadratic-is-reimagining-the-spreadsheet-with-a-focus-on-data/)                                                 
| Hailo lands $120 million to keep battling Nvidia as most AI chip startups struggle            | 2024-04-02 | [Link](https://techcrunch.com/2024/04/02/hailo-ai-chip-startup-lands-120m-to-battle-nvidia/)                                                            
| Seso is building software to fix farm workforces and solve agriculture’s HR woes              | 2024-04-02 | [Link](https://techcrunch.com/2024/04/02/seso-is-building-software-to-fix-farm-workforces-and-solve-agricultures-hr-woes/)                                
| TechCrunch Early Stage 2024 Women’s Breakfast: Exploring AI’s impact on founders              | 2024-04-02 | [Link](https://techcrunch.com/2024/04/02/techcrunch-early-stage-2024-womens-breakfast-exploring-ais-impact-on-founders/)                                 
| Autism Impact Fund closes $60 million first fund and broadens its scope                       | 2024-04-02 | [Link](https://techcrunch.com/2024/04/02/autism-impact-fund/)                                                                                           
| Animal-free egg protein startup Onego Bio is one step closer to cracking the traditional egg market | 2024-04-01 | [Link](https://techcrunch.com/2024/04/01/animal-free-egg-protein-onego-bio-40m/)                                                                         
| Footage from 2020 shows Astra rocket exploding during prelaunch testing                      | 2024-04-01 | [Link](https://techcrunch.com/2024/04/01/astra-rocket-explodes-2020-launch-failure-video-footage/)                                                         
| Why Trump’s digital media company is different from other money-losing startups               | 2024-04-01 | [Link](https://techcrunch.com/2024/04/01/why-trumps-digital-media-company-is-different-from-other-money-losing-startups/)                                  
| Learn startup best practices with Fidelity and others at Early Stage 2024                     | 2024-04-01 | [Link](https://techcrunch.com/2024/04/01/learn-startup-best-practices-with-fidelity-and-others-at-early-stage-2024/)                                        
| Terraform Industries converts electricity and air into synthetic natural gas for the first time | 2024-04-01 | [Link](https://techcrunch.com/2024/04/01/terraform-industries-converted-electricity-and-air-into-synthetic-natural-gas/)                                   
| Ads on Discord, AT&T passcode resets and podcast changes for Android users                   | 2024-04-01 | [Link](https://techcrunch.com/2024/04/01/ads-on-discord-att-passcode-resets-and-podcast-changes-for-android-users/)                                         
| Robinhood’s new Gold Card, BaaS challenges and the tiny startup that caught Stripe’s eye     | 2024-03-31 | [Link](https://techcrunch.com/2024/03/31/robinhoods-new-gold-card-baas-challenges-and-the-tiny-startup-that-caught-stripes-eye/)                             
| MIT tool shows climate change could cost Texans a month and a half of outdoor time by 2080    | 2024-03-30 | [Link](https://techcrunch.com/2024/03/30/mit-outdoor-days/)                                                                                                
| Deal Dive: Iron Sheepdog is fixing short-haul trucking from the bottom up                    | 2024-03-30 | [Link](https://techcrunch.com/2024/03/30/iron-sheepdog-is-fixing-short-haul-trucking-from-the-bottom-up/)                                                 
| Nine crypto VCs on why Q1 investments were so hot and how it compares to previous bull market | 2024-03-29 | [Link](https://techcrunch.com/2024/03/29/nine-crypto-vcs-weigh-in-on-why-q1-investments-were-so-hot-and-how-it-compares-to-the-previous-bull-market/) 
| Pitch Deck Teardown: Plantee Innovations’ $1.4M seed deck                                    | 2024-03-29 | [Link](https://techcrunch.com/2024/03/29/sample-seed-pitch-deck-plantee-innovations/)                                                                      
| Databricks’ GPT rival and who’s investing in ‘underdog’ founders                              | 2024-03-29 | [Link](https://techcrunch.com/2024/03/29/databricks-gpt-rival-and-whos-investing-in-underdog-founders/)                                                      
| How a tiny 4-person startup, Supaglue, caught Stripe’s eye                                   | 2024-03-29 | [Link](https://techcrunch.com/2024/03/29/supaglue-stripe-acquire-acquisition/)                                                                              
| Women in AI: Urvashi Aneja is researching the social impact of AI in India                   | 2024-04-01 | [Link](https://techcrunch.com/2024/04/01/women-in-ai-urvashi-aneja-is-researching-the-social-impact-of-ai-in-india/)                                       
| Women in AI: Brandie Nonnecke of UC Berkeley says investors should insist on responsible AI practices | 2024-03-31 | [Link](https://techcrunch.com/2024/03/31/women-in-ai-brandie-nonnecke-of-uc-berkeley-says-investors-should-insist-on-responsible-ai-practices/)            
| Women in AI: Kate Devlin of King’s College is researching AI and intimacy                    | 2024-03-30 | [Link](https://techcrunch.com/2024/03/30/women-in-ai-kate-devlin-of-kings-college-is-researching-ai-and-intimacy/)                                         
| Startups Weekly: Big shake-ups at the AI heavyweights                                          | 2024-03-29 | [Link](https://techcrunch.com/2024/03/29/startups-weekly-ai-shakeups/)                                                                                    


| NewRetirement wants to simplify financial planning for retirement | 2024-03-27 | [Link](https://techcrunch.com/2024/03/27/newretirement-wants-to-simplify-financial-planning-for-retirement/) |
| Musical toy startup Playtime Engineering wants to simplify electronic music making for kids | 2024-03-27 | [Link](https://techcrunch.com/2024/03/27/musical-toy-startup-playtime-engineering-wants-to-simplify-electronic-music-making-for-kids/) |
| Cyvl.ai is bringing data-driven solutions to transportation infrastructure | 2024-03-27 | [Link](https://techcrunch.com/2024/03/27/cyvl-ai-is-bringing-data-driven-solutions-to-transportation-infrastructure/) |
| Century Health, now with $2M, taps AI to give pharma access to good patient data | 2024-03-27 | [Link](https://techcrunch.com/2024/03/27/century-health-2m-ai-pharma-patient-data/) |
| Act fast — just 3 days remain to grab your TechCrunch Early Stage 2024 tickets | 2024-03-27 | [Link](https://techcrunch.com/2024/03/27/act-fast-just-3-days-remain-to-grab-your-techcrunch-early-stage-2024-tickets/) |
| A comprehensive list of 2023 & 2024 tech layoffs | 2024-03-27 | [Link](https://techcrunch.com/2024/03/27/tech-layoffs-2023-list/) |
| New study of unicorn founders finds most are ‘underdogs,’ and female founders are rising | 2024-03-27 | [Link](https://techcrunch.com/2024/03/27/unicorn-founders/) |
| Wase zaps microbes to squeeze more biogas from wastewater sludge | 2024-03-27 | [Link](https://techcrunch.com/2024/03/27/wase-seed-fundraise/) |
| Marissa Mayer’s startup just rolled out photo sharing and event planning apps, and the internet isn’t sure what to think | 2024-03-27 | [Link](https://techcrunch.com/2024/03/27/marissa-mayers-startup-just-rolled-out-apps-for-group-photo-sharing-and-event-planning-and-the-internet-isnt-sure-what-to-think/) |
| PayPal backs Indonesian insurance startup Qoala in $47M funding | 2024-03-26 | [Link](https://techcrunch.com/2024/03/26/paypal-backs-indonesia-insurance-startup-qoala-in-47m-funding/) |
| Discipulus Ventures mentors young founders to revive a Norman Rockwell vision of America | 2024-03-26 | [Link](https://techcrunch.com/2024/03/26/discipluus-ventures-mentors-founders-norman-rockwell-america/) |
| Vibrant Planet uses AI for land mapping and improving climate resiliency | 2024-03-26 | [Link](https://techcrunch.com/2024/03/26/vibrant-planet-uses-ai-for-land-mapping-and-improving-climate-resiliency/) |
| Synctera is the latest banking-as-a-service startup to lay off staff | 2024-03-26 | [Link](https://techcrunch.com/2024/03/26/baas-startup-synctera-layoffs-fintech/) |
| Evari turns to rocket science to solve problems with heat pumps | 2024-03-26 | [Link](https://techcrunch.com/2024/03/26/evari-seed-round/) |
| Instagram co-founders’ AI-powered news app Artifact may not be shutting down after all | 2024-03-26 | [Link](https://techcrunch.com/2024/03/26/instagram-co-founders-ai-powered-news-app-artifact-may-not-be-shutting-down-after-all/) |
| TechCrunch Minute: What Stability AI’s CEO departure means for other AI startups | 2024-03-26 | [Link](https://techcrunch.com/2024/03/26/techcrunch-minute-what-stability-ais-ceo-departure-means-for-other-ai-startups/) |
| Confetti, a team-building platform used by Apple, Google and Microsoft, raises $16M | 2024-03-26 | [Link](https://techcrunch.com/2024/03/26/confetti-a-team-building-platform-used-by-apple-google-and-microsoft-raises-16m/) |
| Former Nextdoor exec raises $25 million for PipeDreams, a startup rolling up HVAC companies | 2024-03-26 | [Link](https://techcrunch.com/2024/03/26/former-nextdoor-exec-raises-25-million-for-pipedreams-a-startup-rolling-up-hvac-companies/) |
| Ionobell is turning to recycled silicon to boost EV range | 2024-03-26 | [Link](https://techcrunch.com/2024/03/26/ionobell-fundraise-exclusive/) |
| Fireworks.ai open source API puts generative AI in reach of any developer | 2024-03-26 | [Link](https://techcrunch.com/2024/03/26/fireworks-ai-open-source-api-puts-generative-ai-in-reach-of-any-developer/) |

### 📫 Contact

**Tiffany Nguyen**  
📧 [tiffany.nguyen1@alumni.scu.edu](mailto:tiffany.nguyen1@alumni.scu.edu)
