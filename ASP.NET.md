## ASP.NET 
✅ .NET Core এবং .NET Framework এর পার্থক্য, আর্কিটেকচার, মাইগ্রেশন চ্যালেঞ্জ, এবং ডিপ ডাইভ কনসেপ্টগুলো নিচে বিস্তারিত আলোচনা করা হলো: <br> 
.NET Core vs. .NET Framework : <br> 
```
বৈশিষ্ট্য (Feature)            |             .NET Framework                        |      .NET Core / .NET (আধুনিক সংস্করণ)
-------------------------------------------------------------------------------------------------------------------------------------------------------------
আর্কিটেকচার (Architecture)  |  "Monolithic (মনোলিথিক): বিশাল, একক প্যাকেজ।"     |  "Modular (মডুলার): ছোট, স্বাধীন প্যাকেজ (NuGet Packages) এ বিভক্ত।"
প্ল্যাটফর্ম (Platform)         |   Windows Only: শুধুমাত্র উইন্ডোজ অপারেটিং সিস্টেমে চলে।  |  "Cross-Platform: Windows, macOS, এবং Linux-এ চলে।"
ওপেন সোর্স (Open Source)   |   Closed Source: আংশিক ওপেন সোর্স।                  |   Open Source: সম্পূর্ণ ওপেন সোর্স (MIT License)।
পারফরম্যান্স (Performance)  |   তুলনামূলকভাবে কম।                                 |   Significantly Higher: উন্নত JIT কম্পাইলার এবং অপটিমাইজেশনের কারণে অনেক দ্রুত।
বিল্ডিং ব্লক                  |   "Application Domains, System.Web, web.config"     |   "Dependency Injection, Middleware, appsettings.json"
হোস্টিং (Hosting)           |   IIS (Internet Information Services)               |    Kestrel Web Server (Built-in) এবং IIS/Nginx/Apache এর পেছনে।
```




