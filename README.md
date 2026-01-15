# Museum Planning Pipeline

A modern, responsive web dashboard for tracking museum consulting projects, proposals, and client relationships. Built for museum professionals who need a simple yet powerful way to manage their business development pipeline.

🔗 **Live Dashboard:** [https://museumplanning.github.io/pipeline/](https://museumplanning.github.io/pipeline/)

![Dashboard Preview](https://img.shields.io/badge/Status-Active-success)
![Auto-Save](https://img.shields.io/badge/Feature-Auto--Save-blue)
![Privacy](https://img.shields.io/badge/Privacy-Local--Only-green)

---

## ✨ Features

### 📊 Pipeline Management
- **Visual Dashboard** - See all active projects at a glance
- **Real-time Statistics** - Track total value, weighted probability, and high-value opportunities
- **Smart Filtering** - Filter by status: Leads, Proposals, Interviewed, Declined
- **Instant Search** - Search across projects, clients, contacts, and notes

### 💾 Data Management
- **Auto-Save** - Every change saves automatically to your browser
- **Import/Export** - Download backups and restore from JSON files
- **Never Lose Work** - Data persists across browser sessions
- **Privacy First** - All data stays on your computer

### 📧 Contact Management
- **Email Integration** - Click to email individual contacts
- **Email All Contacts** - One-click to email all project contacts
- **Contact Notes** - Track communication history with each contact
- **Contact Roles** - Organize contacts by their role in each project

### 📱 Mobile Friendly
- Fully responsive design
- Works on desktop, tablet, and mobile
- Touch-friendly interface

---

## 🚀 Quick Start

### Option 1: Use the Live Version (Easiest)
1. Go to [https://museumplanning.github.io/pipeline/](https://museumplanning.github.io/pipeline/)
2. Start using immediately - no setup required!
3. Your data auto-saves to your browser

### Option 2: Run Locally
1. Download `index.html` from this repository
2. Double-click the file to open in your browser
3. Bookmark the file location for easy access

---

## 📖 How to Use

### Adding a Project
1. Click the **"+ Add Project"** button
2. Fill in project details:
   - Title (required)
   - Client name
   - Status (Lead, Proposal, Interviewed, etc.)
   - Probability (High 80%, Medium 40%, Low 5%, etc.)
   - Financial value
   - Next action
   - Internal notes
3. Click **"Save Project"**

### Editing a Project
1. Click on any project to expand details
2. Click **"Edit Project"** button
3. Update information
4. Changes save automatically

### Managing Contacts
- Contacts are stored with each project
- Click email addresses to send emails
- Use **"Email All Contacts"** to message everyone at once
- Add notes to track communication history

### Filtering & Searching
- Use filter buttons to show specific statuses
- Type in search box to find projects instantly
- Search works across all fields including contact names

### Backing Up Your Data
1. Click **"Download Backup"** anytime
2. Saves a JSON file with all your data
3. Store this file safely (recommended: weekly backups)

### Restoring Data
1. Click **"Import Backup"**
2. Select your backup JSON file
3. Confirm to restore

---

## 📊 Understanding the Dashboard

### Statistics Cards

**Active Projects**
- Shows projects that are not declined and have probability > 0%

**Total Pipeline Value**
- Sum of all active project values

**Weighted Value**
- Pipeline value adjusted by probability
- Formula: `Project Value × Probability %`
- Example: $100,000 project at 40% = $40,000 weighted value

**High Probability**
- Count of projects with 60%+ probability

### Status Types

| Status | Meaning | Color |
|--------|---------|-------|
| Lead / Follow-up Required | Initial contact stage | Yellow |
| Proposal Submitted | Awaiting proposal decision | Blue |
| Interviewed | Past interview stage | Purple |
| Declined | Not moving forward | Red |

### Probability Levels

- **High (80%)** - Very likely to close
- **Medium-High (60%)** - Good chance
- **Medium (40%)** - 50/50 odds
- **Medium-Low (30%)** - Possible but uncertain
- **Low (5%)** - Unlikely
- **Zero** - No chance (use for declined projects)

---

## 🔒 Privacy & Data Security

### Where Your Data Lives
- ✅ **Browser Local Storage** - All data stays on your computer
- ✅ **No Server** - Nothing is sent to external servers
- ✅ **No Tracking** - No analytics or tracking code
- ✅ **Offline Capable** - Works without internet after first load

### Data Safety
- Auto-saves prevent data loss
- Download backups for redundancy
- Browser storage survives restarts
- Import/export for transferring data

### Important Notes
- Each browser/device has separate data
- Clearing browser data will delete the pipeline
- Always keep backup JSON files
- For multi-device use, manually transfer via backup files

---

## 🛠️ Technical Details

### Built With
- Pure HTML, CSS, and JavaScript
- No dependencies or frameworks
- No build process required
- Uses browser LocalStorage API

### Browser Compatibility
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers

### File Size
- Single HTML file: ~30KB
- No external dependencies
- Fast loading

---

## 📁 Project Structure

```
museum-pipeline/
├── index.html          # Main dashboard (complete application)
├── README.md           # This file
└── backups/           # (Optional) Store your backup files here
```

---

## 🤝 Contributing

This is a personal project, but suggestions are welcome!

### Reporting Issues
If you find a bug or have a feature request:
1. Download a backup of your data first
2. Open an issue describing the problem
3. Include browser version and steps to reproduce

---

## 📝 Changelog

### Version 2.0 (Current)
- ✅ Email contact buttons
- ✅ "Email All Contacts" feature
- ✅ Import backup functionality
- ✅ Enhanced contact display with notes
- ✅ Improved mobile responsiveness
- ✅ Success/error alerts

### Version 1.0
- Initial release
- Basic pipeline tracking
- Auto-save functionality
- Search and filter
- Export backups

---

## ❓ FAQ

**Q: Will I lose my data if I close the browser?**
A: No! Your data auto-saves and persists across sessions.

**Q: Can I use this on multiple computers?**
A: Yes, but you need to manually transfer data using backup files.

**Q: What happens if I clear my browser data?**
A: Your pipeline data will be deleted. Always keep backup files!

**Q: Can others see my data?**
A: No. All data stays in your browser on your computer.

**Q: Is there a mobile app?**
A: The web version works great on mobile browsers. Just bookmark it!

**Q: Can I customize the status options?**
A: Currently no, but this could be added in a future update.

**Q: How do I update to a new version?**
A: Download your backup, then replace the old HTML file with the new one. Import your backup to restore data.

---

## 📞 Support

For questions or support:
- Open an issue on GitHub
- Email: [Your email if you want to include it]

---

## 📄 License

This project is open source and available for personal and commercial use.

---

## 🙏 Acknowledgments

Built for museum professionals who need simple, effective project tracking without complex CRM systems.

---

**Last Updated:** January 2026

**Version:** 2.0

