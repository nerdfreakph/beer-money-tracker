# **Beer Money Tracker**

## **Purpose**
Beer Money Tracker is a lightweight web app that helps users track small income or side hustle earnings (“beer money”), record spending, and visualize totals over time.  
It’s designed for simplicity and quick entry, making financial tracking effortless.

## **Features**

### **Apps & Currencies Management**
- Add, edit, or delete apps you earn money from.  
- Add, edit, or delete currencies (e.g., PHP, USD).

### **Beer Money Entries**
- Add new income entries with: App, Currency, Amount, Date, and Remarks.  
- Entries are stored in the browser’s local storage (no backend needed).

### **Tracking & Stats**
- Displays weekly total and overall total earnings.  
- Dynamic table lists all entries with a delete option.

### **Charts**
- Interactive chart visualizing earnings over time.  
- Toggle between “Per App” and “Total All Apps” view.

### **Responsive & Modern UI**
- Built with TailwindCSS.  
- Fully responsive layout suitable for desktop and mobile.

### **Persistence**
- Uses localStorage to remember apps, currencies, entries, and chart mode between sessions.

## **Tech Stack**
- **Frontend:** HTML, TailwindCSS, JavaScript, Chart.js  
- **Storage:** Browser localStorage  
- **Charts:** Chart.js for interactive visualization

## **How It Works**
1. Add your apps and currency.  
2. Record each “beer money” entry with date, amount, and remarks.  
3. View weekly and total stats at a glance.  
4. Use the chart to visualize income trends per app or combined.

## **Future Updates**
- Auto Conversion using API  
- User Accounts for multiple user capability  
- Import/Export entries to CSV/Excel  
- Integrate backend storage for permanent record-keeping  
- Add notifications or reminders for tracking earnings
