📘 Bookstore Web Scraping Project using Scrapy
Summary:

Developed a complete end-to-end web scraping project using the Scrapy framework to extract structured data from an online bookstore containing 1,000+ books across 50 web pages.

Key features include:

🔍 Data Extraction: Scraped detailed book information such as title, price, rating, availability, and category from all paginated sections of the target website.

📁 Data Storage: Stored raw data efficiently in both JSON and CSV formats for flexibility in downstream usage.

🧼 Pipeline Implementation: Built a Scrapy pipeline to clean, validate, and transform the data before final storage.

🛢️ MySQL Integration: Integrated real-time storage of the processed book data into a MySQL database, enabling live querying and analytics.

🛡️ Middleware Enhancement:

Implemented custom headers and rotating IP proxies through Scrapy’s middleware to avoid IP bans and improve reliability.

Enhanced bot evasion through dynamic user-agent rotation and spoofed request headers.

Tech Stack: Python, Scrapy, MySQL, JSON, CSV, Git, GitHub
