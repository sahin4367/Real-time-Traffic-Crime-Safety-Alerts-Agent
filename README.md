# Real-time-Traffic-Crime-Safety-Alerts-Agent

This project is a **real-time alert agent** built on **n8n + Bright Data + OpenAI + Google Maps + Email**.
The goal is to inform people about traffic accidents and crime incidents in time and **increase safety and avoid fines**.

---

## ✨ Goal
- Retrieving data from **Google News** with real-time web scraping
- **Improving and explaining news in a short and clear way** through OpenAI
- Displaying dangerous areas with **Google Maps link**
- **Sending the final result to the user via email**

---

## 🛠 Technologies Used
- **[n8n](https://n8n.io/)** – Workflow automation platform
- **[Bright Data](https://brightdata.com/)** – Real-time web data for Google News scraping
- **[OpenAI](https://platform.openai.com/)** – Improving and analyzing news
- **[Google Maps API](https://developers.google.com/maps/documentation/geocoding/overview)** – Linking dangerous areas on the map
- **Email (SMTP/Gmail)** – Sending security alerts to the user

---

## ⚙️ Installation and Usage
1. Download the `workflow.json` file and import it into **n8n**
2. Add the required **API keys**:
- Bright Data API Key
- OpenAI API Key
- Google Maps API Key
- SMTP/Gmail details (for sending emails)
3. Set the workflow's running interval (e.g. every 30 minutes) by changing the `Schedule Trigger` node
4. Run the workflow → the news will be analyzed and **sent as email**

---

## 📧 Sample Email
<img width="1901" height="937" alt="image" src="https://github.com/user-attachments/assets/7db5d2ac-7cdc-4fcb-8926-9a577f8233b7" />
<img width="1895" height="888" alt="image" src="https://github.com/user-attachments/assets/9fb668c5-0b69-4f3a-b119-42fdbef74f38" />
<img width="1889" height="970" alt="image" src="https://github.com/user-attachments/assets/1b606c4a-49e7-48b3-8613-526b66629558" />


