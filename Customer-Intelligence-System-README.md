
# Customer Intelligence System

### Overview  
The **Customer Intelligence System** showcases how a unified data foundation can power both **analytics and AI-driven engagement** for a retail platform like Instacart.  
It combines **customer segmentation analytics** with **AI-based retention personalization**, demonstrating how structured data and automation together enhance customer understanding and enable an AI-based solution to increase engagement.

### Core Idea  
As analytics evolves toward conversational and predictive systems, this project builds a single, well-modeled data layer (Bronze → Silver → Gold) that supports both insight generation and AI integration.  
It enables:  
- **Customer segmentation** and behavioral analysis from unified data.  
- **AI-powered personalized notifications** for retention and engagement.


### Key Highlights  
- 🧩 **Data Modeling:** Medallion Architecture with Delta tables for clean, reusable layers.  
- 📈 **Analytics:** Dashboards showing customer segments, order frequency, and activity patterns.  
- 🤖 **AI Integration:** OpenAI-based notification generator using behavioral context from the table in Gold layer.  


### Preview  

**📊Dashboard Snapshot**

<img width="719" height="602" alt="Screenshot 2025-10-29 at 10 54 41 AM" src="https://github.com/user-attachments/assets/f354f6e7-4107-456a-9642-0dfb841a11da" />
<br></br>
**💬 Sample AI Notifications**

*1. Restock gently and get your favorite Classic Vanilla Yogurt back into your kitchen tonight.*

*2. Refresh your Tuesday with a cool sip of Natural Artesian Water. Grab it now and save 10% on your order!*

*3. Your usual essentials are just a tap away this Friday evening. Enjoy the convenience and order now.*

*4. Morning is a great time to add Organic Baby Rainbow Carrots to your cart. Time to refresh your pantry!*

*5. Get your Everyday 2 Ply Premium Napkins and enjoy 10% off your order. Shop today!*

### Full Article  
Read the detailed project explanation here:  
👉 [Read on Medium](#)

### Tech Stack  
Databricks • Azure Data Lake • Python • SQL • OpenAI API  
