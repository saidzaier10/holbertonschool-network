# 🌐 What Happens When You Type google.com

## 📋 Project Overview

This project explores the complete journey of a web request - from typing `https://www.google.com` in your browser to seeing the Google homepage. It's a deep dive into web infrastructure that every software engineer should understand.

## 🎯 Learning Objectives

By completing this project, you will understand:
- How DNS resolution works
- The TCP/IP protocol stack
- Security layers (Firewalls, SSL/TLS)
- Load balancing mechanisms
- Server architecture (Web, Application, Database)
- The complete request/response cycle

## 📁 Repository Structure

```
holbertonschool-network/
└── what_happens_when_your_type_google_com_in_your_browser_and_press_enter/
    ├── 0-blog_post
    ├── 1-what_happen_when_diagram
    └── README.md
```

## 📝 Project Requirements

### Task 0: Blog Post
Write a comprehensive blog post explaining what happens when you type `https://www.google.com` and press Enter.

**Must cover:**
- ✅ DNS request
- ✅ TCP/IP
- ✅ Firewall
- ✅ HTTPS/SSL
- ✅ Load-balancer
- ✅ Web server
- ✅ Application server
- ✅ Database

**Publication:** LinkedIn

### Task 1: Diagram
Create a visual diagram illustrating the request flow.

**Must show:**
- ✅ DNS resolution process
- ✅ Request hitting server IP on port 443
- ✅ Encrypted traffic (HTTPS)
- ✅ Traffic passing through firewall
- ✅ Load balancer distribution
- ✅ Web server response
- ✅ Application server generating content
- ✅ Database queries

**Tool Used:** MermaidChart

## 🔗 Deliverables

### Blog Post
**URL:** [LinkedIn Post - What Happens When You Type google.com](https://www.linkedin.com/posts/said-zaier_webarchitecture-networking-techeducation-activity-7378048177918148608-UQc0)

**Platform:** LinkedIn

**Status:** ✅ Published

### Diagram
**URL:** [Network Request Flow Diagram](https://www.mermaidchart.com/d/07335f04-90b0-4a68-a184-41097d2f2f6d)

**Tool Used:** MermaidChart

**Status:** ✅ Completed

## 🚀 Key Concepts Explained

### DNS Resolution
Translates domain names to IP addresses through a hierarchical query system, checking multiple cache levels before querying root servers.

### TCP/IP
Establishes reliable connections using the three-way handshake (SYN, SYN-ACK, ACK) ensuring both parties are ready to communicate.

### Firewall
Security checkpoints at multiple levels (local, router, ISP, server) that filter traffic and protect against malicious requests.

### HTTPS/SSL
Creates an encrypted tunnel using TLS certificates and session keys, ensuring data privacy during transmission.

### Load Balancer
Distributes incoming requests across thousands of servers using algorithms like round-robin and geographic routing to prevent overload.

### Web Server
Handles HTTP request processing, serves static content, routes to application servers, and manages response compression.

### Application Server
Executes business logic, checks authentication, personalizes content, and generates dynamic HTML responses.

### Database
Stores and retrieves user data using distributed systems like Bigtable and Spanner for speed and reliability.

## 💡 Why This Matters

Understanding this process is crucial for:
- **Debugging** - Identify where issues occur in the stack
- **Performance** - Optimize each layer for speed
- **Security** - Understand attack vectors and defenses
- **System Design** - Build scalable architectures
- **Interviews** - Common technical interview question

## 📚 Resources

- [MDN Web Docs - How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- [High Performance Browser Networking](https://hpbn.co/)
- [DNS Explained](https://www.cloudflare.com/learning/dns/what-is-dns/)
- [TCP/IP Guide](https://www.tcpipguide.com/)
- [MermaidChart Documentation](https://www.mermaidchart.com/docs/)

## 🛠️ Technologies Covered

- **Protocols:** HTTP/HTTPS, TCP/IP, DNS, SSL/TLS
- **Infrastructure:** Load Balancers, Firewalls, CDNs
- **Servers:** Nginx, Apache, Application Servers
- **Databases:** Bigtable, Spanner, Caching layers
- **Security:** Encryption, Certificate Authorities, Firewalls
- **Tools:** MermaidChart for diagramming

## 📱 Social Media & Professional Presence

This project has been shared on:
- **LinkedIn Post:** [Published Article](https://www.linkedin.com/posts/said-zaier_webarchitecture-networking-techeducation-activity-7378048177918148608-UQc0)
- **Engagement Goal:** Start conversations about web infrastructure
- **Learning in Public:** Part of my journey at Holberton School

## 👤 Author

**Said Zaier**
- GitHub: [@saidzaier10](https://github.com/saidzaier10)
- LinkedIn: [Said Zaier](https://www.linkedin.com/in/said-zaier/)

## 📄 License

This project is part of the Holberton School curriculum.

---

*"Understanding the infrastructure behind every click makes you a better engineer."*