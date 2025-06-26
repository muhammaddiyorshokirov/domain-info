Free Domain Info API
====================

Need to check technical details about any domain? Here's a free and reliable Domain Info API! 🛠🔍

🌟 API URL:
-----------

`https://s741890.stase.uz/api/domain-info.php?domain=YOUR_DOMAIN`

For example:

    https://s741890.stase.uz/api/domain-info.php?domain=google.com

This will return DNS and technical info about **google.com**

*   ✅ 100% free
*   ✅ No ads or registration
*   ✅ No payment required
*   ✅ Simple HTTP GET request
*   ✅ Clean JSON response

📦 Example Response:
--------------------

    {
      "status": "success",
      "message": "DNS query completed successfully",
      "timestamp": "2025-06-26T10:50:55+03:00",
      "data": {
        "domain": "google.com",
        "ip": {
          "primary": "216.58.212.142",
          "all": ["216.58.212.142"],
          "ipv6": "2a00:1450:4001:801::200e"
        },
        "dns_records": {
          "nameservers": [...],
          "mail_servers": [...],
          "txt_records": [...],
          "soa_record": {...},
          "caa_records": [...],
          "spf": "v=spf1 include:_spf.google.com ~all"
        },
        "ttl": 300,
        "dns_servers_used": ["smtp.google.com"]
      }
    }

🔍 What info can you get?
-------------------------

*   🌍 IP address (IPv4 & IPv6)
*   📩 Mail servers
*   🧭 Name servers
*   🧾 TXT, SPF, SOA records
*   ⏱️ TTL, DNS query time, and more

🚀 Perfect for developers, domain monitoring tools, or security dashboards.


[![Join Telegram](https://img.shields.io/badge/Telegram-Join_Channel-blue?logo=telegram)](https://t.me/codegateuz)
