---
layout: default
title: "SOMOS.tech FAQ"
permalink: /
---

# Frequently Asked Questions (FAQ)

## ⚠️ Important Notice: US Service Availability

**SOMOS.tech services are currently only available to users located in the United States.**

As part of our cost reduction efforts for AI programs and infrastructure optimization, we have implemented geographic restrictions on our platform. Access to SOMOS.tech is limited to users within the United States only.

**Why this restriction?**
- **AI Cost Management**: Azure AI and OpenAI services incur significant costs. Limiting to US traffic helps us manage these expenses while maintaining service quality.
- **Compliance & Optimization**: Geographic restrictions allow us to optimize infrastructure costs and ensure compliance with regional requirements.
- **Future Expansion**: We are actively evaluating options to expand service availability to other regions as funding and resources allow.

**What if I'm outside the US?**
Currently, access from outside the United States will be blocked by our Web Application Firewall (WAF). We appreciate your interest and encourage you to check back for updates on expanded availability.

---

## Services

### What is SOMOS.tech?

SOMOS.tech is a modern event management and community platform designed for Latino professionals and community members. Our platform provides tools for networking, professional development, and community engagement.

### What services does SOMOS.tech offer?

- **Event Management**: Discover and register for community events, workshops, and networking opportunities
- **Community Groups**: Join professional groups based on interests, industries, and career goals
- **Professional Networking**: Connect with other Latino professionals and community members
- **Real-Time Messaging**: Participate in community discussions and group chats
- **Profile Management**: Create and maintain your professional profile
- **Donation Platform**: Support the SOMOS.tech mission through our Givebutter integration

### Is SOMOS.tech free to use?

Yes! SOMOS.tech is a free platform for all members. We are supported through donations and community contributions. If you'd like to support our mission, you can make a donation at [givebutter.com/somostech](https://givebutter.com/somostech).

### What technologies power SOMOS.tech?

SOMOS.tech is built on modern, secure cloud technologies:
- **Frontend**: React 19 with TypeScript and Tailwind CSS
- **Backend**: Azure Functions (serverless)
- **Database**: Azure Cosmos DB
- **Authentication**: Dual authentication system (Azure AD for admins, Auth0 for members)
- **Real-Time Features**: Azure SignalR Service
- **AI Moderation**: Azure OpenAI for content safety
- **Hosting**: Azure Static Web Apps with Azure Front Door CDN
- **Security**: Web Application Firewall (WAF) with geo-blocking and threat protection

---

## Account & Privacy

### How do I create an account?

1. Visit [dev.somos.tech](https://dev.somos.tech)
2. Click "Sign Up" or "Member Portal"
3. Choose your authentication method:
   - Sign in with Google
   - Sign in with Microsoft
   - Create an account with email and password
4. Complete your profile information
5. Start connecting with the community!

### What authentication options are available?

SOMOS.tech uses Auth0 for secure member authentication. You can sign in using:
- **Google Account**: OAuth integration
- **Microsoft Account**: OAuth integration
- **Email & Password**: Traditional authentication
- **LinkedIn**: OAuth integration (where supported)

### Can I link multiple accounts?

Yes! SOMOS.tech supports account linking. If you sign in with different providers using the same email address (e.g., Google and LinkedIn), our system will recognize and link your accounts automatically. You'll have a stable platform ID (`somosUserId`) that remains consistent regardless of which provider you use to log in.

### How is my data protected?

We take security seriously. Your data is protected through:
- **Encryption**: TLS 1.3 for data in transit, encryption at rest for stored data
- **Private Networking**: Backend services use Azure Private Endpoints (no public internet exposure)
- **Authentication**: Industry-standard OAuth 2.0 and OpenID Connect protocols
- **Content Moderation**: AI-powered 3-tier moderation system to ensure safe community interactions
- **Access Controls**: Role-based access control (RBAC) and managed identities
- **Compliance**: SOC 2, GDPR, and HIPAA-ready security architecture

### What information do you collect?

We collect only the information necessary to provide our services:
- **Profile Information**: Name, email, profile photo, professional details you choose to share
- **Authentication Data**: Provider IDs, login timestamps (managed by Auth0)
- **Usage Data**: Event registrations, group memberships, messages you send
- **Technical Data**: Anonymous analytics for service improvement (Application Insights)

We **do not**:
- Sell your data to third parties
- Share your personal information without your consent
- Track you across other websites

### How do I delete my account?

To delete your account:
1. Sign in to your SOMOS.tech account
2. Go to your Profile page
3. Scroll to the bottom and click "Delete Account"
4. Confirm your decision

**Note**: Account deletion is permanent and cannot be undone. All your data, including profile information, messages, and event registrations, will be permanently removed from our systems within 30 days.

### Can I export my data?

Yes! Under GDPR and privacy regulations, you have the right to export your data. Contact our support team at **support@somos.tech** to request a data export. We will provide your data in a machine-readable format (JSON) within 30 days.

---

## Support

### How do I get help?

If you need assistance, you can:

1. **Check this FAQ**: Many common questions are answered here
2. **Email Support**: support@somos.tech
3. **Review Documentation**: Visit our [GitHub repository](https://github.com/somos-tech/somos-tech-v2) for technical documentation
4. **Report Issues**: File an issue on our [GitHub Issues page](https://github.com/somos-tech/somos-tech-v2/issues)

### What are your support hours?

Our volunteer support team typically responds within:
- **Email Support**: 24-48 hours during business days
- **Critical Issues**: Within 24 hours for security or access issues
- **General Questions**: 2-5 business days

Please note that SOMOS.tech is run by a volunteer team, so response times may vary during holidays and weekends.

### I found a bug. How do I report it?

We appreciate bug reports! Please:
1. Visit our [GitHub Issues page](https://github.com/somos-tech/somos-tech-v2/issues)
2. Check if the bug has already been reported
3. If not, create a new issue with:
   - A descriptive title
   - Steps to reproduce the bug
   - Expected vs. actual behavior
   - Screenshots (if applicable)
   - Your browser and operating system

### I have a feature request. Where do I submit it?

We welcome feature suggestions! Please:
1. Visit our [GitHub Issues page](https://github.com/somos-tech/somos-tech-v2/issues)
2. Create a new issue with the label "enhancement"
3. Describe the feature and how it would benefit the community
4. Our team will review and prioritize based on community needs and available resources

### Is SOMOS.tech open source?

Yes! SOMOS.tech is an open-source project. You can:
- View our source code on [GitHub](https://github.com/somos-tech/somos-tech-v2)
- Contribute code improvements
- Report issues and suggest features
- Review our documentation and architectural decisions

See our [Contributing Guide](https://github.com/somos-tech/somos-tech-v2/blob/main/CONTRIBUTING.md) for more information on how to get involved.

---

## Location & Availability

### Why is SOMOS.tech only available in the United States?

SOMOS.tech currently restricts access to users in the United States as part of our cost optimization strategy. Key reasons include:

1. **AI Service Costs**: Our platform uses Azure OpenAI for content moderation and AI features, which incur per-request costs. Limiting geographic scope helps control these expenses.
2. **Infrastructure Optimization**: Focusing on a single region allows us to optimize CDN, edge computing, and data storage costs.
3. **Regulatory Compliance**: Operating in a single jurisdiction simplifies compliance with data protection and privacy regulations.
4. **Sustainable Growth**: This approach allows us to maintain high service quality while operating within our budget constraints.

### When will SOMOS.tech be available in other countries?

We are actively planning for international expansion. Future availability depends on:
- **Funding**: Securing grants or donations to cover increased infrastructure costs
- **Partnership Opportunities**: Collaborating with organizations to sponsor regional expansion
- **Community Demand**: Demonstrated interest from international Latino communities
- **Technical Readiness**: Implementing multi-region infrastructure and compliance requirements

**Target Regions for Future Expansion**:
- 🇨🇦 Canada
- 🇲🇽 Mexico
- 🇬🇧 United Kingdom
- 🇪🇺 European Union (Spain, Germany, France)
- 🌎 Latin America (priorities based on community feedback)

### How can I stay updated on expansion plans?

To receive updates about SOMOS.tech expansion:
1. **Star our GitHub repository**: [somos-tech/somos-tech-v2](https://github.com/somos-tech/somos-tech-v2)
2. **Watch for announcements**: Follow our GitHub discussions
3. **Email us**: Contact support@somos.tech to join our international interest list
4. **Community Forums**: Participate in discussions about expansion plans

### Can I access SOMOS.tech with a VPN?

**No**. Using a VPN to bypass geographic restrictions is against our terms of service and will result in:
- Access denied by our Web Application Firewall (WAF)
- Potential account suspension
- Blocked IP addresses

Our WAF is configured to block known VPN providers, proxy services, and Tor exit nodes. Please respect our geographic limitations as they are essential for maintaining service sustainability.

---

## Technical Details

### What browsers are supported?

SOMOS.tech supports modern, evergreen browsers:
- ✅ Google Chrome (latest 2 versions)
- ✅ Mozilla Firefox (latest 2 versions)
- ✅ Microsoft Edge (latest 2 versions)
- ✅ Safari (macOS/iOS, latest 2 versions)
- ⚠️ Older browsers (Internet Explorer, legacy versions) are not supported

### Is there a mobile app?

Currently, SOMOS.tech is a progressive web application (PWA) accessible through mobile browsers. A dedicated native mobile app is planned for future development based on community demand and resources.

### What are the system requirements?

Minimum requirements:
- **Internet Connection**: Broadband or 4G/5G (minimum 1 Mbps)
- **Browser**: Modern evergreen browser (see above)
- **JavaScript**: Must be enabled
- **Cookies**: Must be enabled for authentication
- **Screen Resolution**: Minimum 375px width (mobile-responsive)

### Does SOMOS.tech work offline?

No, SOMOS.tech requires an active internet connection for all features. Real-time messaging, event updates, and profile synchronization require constant connectivity.

---

## Community Guidelines

### What are the community rules?

SOMOS.tech is committed to maintaining a safe, respectful, and inclusive community. All members must:
- ✅ Treat others with respect and professionalism
- ✅ Avoid hate speech, harassment, or discriminatory language
- ✅ Refrain from spam, scams, or promotional content (unless authorized)
- ✅ Protect the privacy of other members
- ✅ Follow event-specific guidelines set by organizers

### What happens if I violate community guidelines?

Violations may result in:
1. **Warning**: First offense (minor violation)
2. **Content Removal**: Inappropriate posts or messages deleted
3. **Temporary Suspension**: 7-30 day account suspension
4. **Permanent Ban**: Serious or repeated violations

### How is content moderated?

SOMOS.tech uses a 3-tier AI-powered moderation system:
1. **Tier 1 - Local Filters**: Instant blocklist matching (profanity, known attacks)
2. **Tier 2 - Azure AI Safety**: Fast detection of hate speech, violence, and harmful content
3. **Tier 3 - Azure OpenAI Analysis**: Detailed semantic analysis for context-aware moderation

All moderation decisions are logged and can be appealed by contacting support@somos.tech.

---

## Contributing & Development

### How can I contribute to SOMOS.tech?

We welcome contributions! You can help by:
- **Code Contributions**: Submit pull requests on [GitHub](https://github.com/somos-tech/somos-tech-v2)
- **Documentation**: Improve our guides and technical docs
- **Bug Reports**: File detailed issue reports
- **Feature Suggestions**: Share ideas for new features
- **Testing**: Help test new features before release
- **Community Support**: Answer questions in discussions
- **Donations**: Support our infrastructure costs at [givebutter.com/somostech](https://givebutter.com/somostech)

### What skills are needed to contribute?

Depending on your interests:
- **Frontend Development**: React, TypeScript, Tailwind CSS
- **Backend Development**: Node.js, Azure Functions, serverless architecture
- **Infrastructure**: Azure, Bicep, CI/CD, DevOps
- **Design**: UI/UX design, accessibility, branding
- **Content**: Technical writing, documentation, translation
- **Community Management**: Moderation, event planning, outreach

### How do I set up a development environment?

See our [Main README](https://github.com/somos-tech/somos-tech-v2/blob/main/README.md) for complete setup instructions. Quick start:

1. Clone the repository
2. Install Node.js 20
3. Install dependencies: `npm install`
4. Configure local settings (Azure credentials)
5. Run frontend: `cd apps/web && npm run dev`
6. Run backend: `cd apps/api && func start`

Detailed setup instructions, including Azure configuration, are available in our documentation.

---

## Still Have Questions?

If your question isn't answered here, please:
- **Email us**: support@somos.tech
- **Open a GitHub Issue**: [github.com/somos-tech/somos-tech-v2/issues](https://github.com/somos-tech/somos-tech-v2/issues)
- **Check our documentation**: [docs/](https://github.com/somos-tech/somos-tech-v2/tree/main/docs)

---

**Last Updated**: January 1, 2026  
**Platform Version**: 2.1  
**Service Region**: United States Only

---

*SOMOS.tech is a community-driven platform built by and for Latino professionals. Together, we're creating opportunities for networking, professional development, and community impact.*
