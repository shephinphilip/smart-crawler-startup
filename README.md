# Startup Directory Web Crawler

This project is a powerful web crawler designed to extract startup exhibitor information from [Startup Mahakumbh 2025](https://startupmahakumbh.org/exhibitor_directory/exhi_list_pub.php). It dynamically parses through all startups listed from A to Z, across all pages, and saves structured data in a CSV.

---

## 📦 Features

-  A–Z alphabetical crawling  
-  Dynamic page count detection  
-  Startup data extraction from HTML content  
-  Auto-retry and polite crawling with delays  
-  Output as clean CSV file

---

##  Data Extracted Per Startup

Each record includes:

- **Name** – Startup name
- **Contact Person** – Point of contact
- **Designation** – Role/title
- **Email** – Contact email
- **Profile** – Description/overview
- **Website** – Link to startup's official page

---

## Setup

### 1. Clone this repository
```bash
git clone https://github.com/yourusername/startup-directory-crawler.git
cd startup-directory-crawler
```

### 2. upload the ipynb file into google colab


The results will be saved as:
```
startup_directory.csv
```

---

## 📂 Output Format

| Name                            | Contact Person     | Designation | Email                   | Profile                 | Website                         |
|---------------------------------|--------------------|-------------|--------------------------|--------------------------|----------------------------------|
| A.K. Gourmet House Pvt. Ltd.    | Mr. Arjun Thakur   | Director    | arjunthakur@ohnuts.in    | Healthy nut-based snacks | https://www.ohnuts.in            |
| Aadvik Foods and Products Pvt Ltd | Mr. Hitesh Rathi | Founder     | hitesh@aadvikfoods.com   | Camel milk products      | https://aadvikfoods.com          |
| ...                             | ...                | ...         | ...                      | ...                      | ...                              |

---

## 🛠 Tech Stack

- `Python 3.8+`
- `BeautifulSoup` – HTML parsing
- `requests` – HTTP calls
- `csv` – Data output

---

## ⚠️ Disclaimer

This script is intended for educational purposes and personal data aggregation.  
Please respect the site's robots.txt and do not overload the server with high-frequency requests.

---

## 🙌 Contributing

Got an idea? Found a bug? PRs and issues are welcome!
