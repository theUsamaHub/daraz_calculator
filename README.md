# Daraz Seller Pro - Advanced Profit Calculator

A comprehensive profit calculation tool designed specifically for Daraz sellers across multiple countries. This calculator helps sellers determine optimal pricing strategies by accounting for all Daraz fees, shipping costs, and profit margins.

## 🌟 Features

### Core Calculator
- **Real-time Price Calculations**: Instantly calculate selling prices based on cost and desired profit margins
- **Multi-Country Support**: Supports Pakistan, Bangladesh, Nepal, Sri Lanka, and Myanmar with country-specific fee structures
- **Currency Support**: Automatic currency conversion and symbol display (PKR, BDT, NPR, LKR, MMK)
- **Fee Customization**: Edit and save custom fee percentages for accurate calculations

### Advanced Features
- **Bulk Product Analysis**: Analyze multiple products simultaneously with CSV export
- **Profit Scenarios**: Generate profit projections across different margin ranges with interactive charts
- **Smart Insights**: Get AI-powered recommendations to optimize your pricing strategy
- **Discount Planning**: Calculate listing prices for different discount scenarios
- **Shipping Cost Integration**: Factor in both shipping costs and buyer payments

### User Experience
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations and transitions
- **Data Persistence**: Saves your fee preferences and calculation history locally
- **Export Options**: Generate detailed reports and share results

## 🚀 Quick Start

1. **Open the Calculator**
   - Open `index.html` in your web browser
   - Or run a local server: `python -m http.server 3000` then visit `http://localhost:3000`

2. **Basic Usage**
   - Enter your product wholesale cost
   - Set your desired profit margin (5-50%)
   - Add shipping costs if applicable
   - View instant calculations for final price, fees, and profit

3. **Customize Fees**
   - Click "Customize Fee Percentages" to edit fee structures
   - Adjust commission, handling, payment, and other fees
   - Changes are automatically saved to your browser

## 📊 Supported Countries & Fee Structures

### Pakistan (PKR)
- Commission + VAT: 16.67%
- Handling Fee: 2.69%
- Payment Fee: 2.59%
- Tax Withholding: 0.94%
- Co-funded Voucher: 2.00%
- Free Shipping Promo: 6.90%
- Net Shipping Cost: 4.04%

### Bangladesh (BDT)
- Commission + VAT: 15.50%
- Handling Fee: 2.50%
- Payment Fee: 2.40%
- Tax Withholding: 0.90%
- Co-funded Voucher: 1.80%
- Free Shipping Promo: 6.50%
- Net Shipping Cost: 3.80%

### Nepal (NPR)
- Commission + VAT: 14.80%
- Handling Fee: 2.30%
- Payment Fee: 2.20%
- Tax Withholding: 1.00%
- Co-funded Voucher: 1.70%
- Free Shipping Promo: 6.20%
- Net Shipping Cost: 3.60%

### Sri Lanka (LKR)
- Commission + VAT: 15.00%
- Handling Fee: 2.40%
- Payment Fee: 2.30%
- Tax Withholding: 0.85%
- Co-funded Voucher: 1.90%
- Free Shipping Promo: 6.40%
- Net Shipping Cost: 3.90%

### Myanmar (MMK)
- Commission + VAT: 14.50%
- Handling Fee: 2.20%
- Payment Fee: 2.10%
- Tax Withholding: 0.80%
- Co-funded Voucher: 1.60%
- Free Shipping Promo: 6.00%
- Net Shipping Cost: 3.50%

## 📈 Calculation Formula

The calculator uses the following formula to determine the optimal selling price:

```
Final Price = Cost / (1 - Total_Fee% - Desired_Profit%)
```

Where:
- **Total_Fee%** = Sum of all Daraz fees (commission, handling, payment, etc.)
- **Desired_Profit%** = Your target profit margin
- **Final Price** = The price customer pays after discounts

## 🛠️ Advanced Features Explained

### Bulk Analysis
Upload multiple products in the format: `ProductName,Cost,DesiredMargin`
- Example: `Wireless Earbuds,500,25`
- Export results to CSV for further analysis
- View ROI calculations for each product

### Profit Scenarios
- Visualize profit potential across different margin ranges
- Interactive charts showing profit vs. margin relationships
- Helps identify optimal pricing strategies

### Smart Insights
- Personalized recommendations based on your cost structure
- Tips for improving profitability
- Market-specific advice for different price points

## 📱 Mobile Compatibility

The calculator is fully responsive and works on:
- Desktop browsers (Chrome, Firefox, Safari, Edge)
- Tablet devices
- Mobile phones (iOS and Android)

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with animations and gradients
- **JavaScript ES6+**: Advanced calculations and interactions
- **Chart.js**: Interactive data visualization
- **Font Awesome**: Professional icons and UI elements

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Data Storage
- **Local Storage**: Saves fee preferences and calculation history
- **No Server Required**: Works completely offline after initial load
- **Privacy**: All data remains on your device

## 📋 File Structure

```
Darazcalculator/
├── index.html          # Main calculator application
├── previous.html       # Previous version (simpler interface)
└── README.md          # This documentation file
```

## 🎯 Use Cases

### For New Sellers
- Calculate your first product pricing
- Understand Daraz's fee structure
- Plan profitable pricing strategies

### For Experienced Sellers
- Optimize existing product prices
- Analyze bulk product portfolios
- Plan discount campaigns

### For Market Research
- Compare profitability across countries
- Analyze market entry strategies
- Forecast revenue scenarios

## ⚠️ Important Notes

1. **Fee Accuracy**: Fee percentages are based on current Daraz policies but may change
2. **Shipping Costs**: Actual shipping costs may vary based on product size and location
3. **Currency Exchange**: For cross-border selling, consider exchange rate fluctuations
4. **Taxes**: Additional local taxes may apply depending on your business structure
5. **Disclaimer**: This tool provides estimates. Always verify with official Daraz policies

## 🔄 Updates & Support

### Version History
- **v2.0**: Multi-country support, bulk analysis, scenarios, insights
- **v1.0**: Basic calculator with customizable fees

### Getting Help
- Check the built-in User Guide (click "User Guide" in the footer)
- Use the feedback option to report issues or suggest features
- Review the calculation formulas for transparency

## 📄 License

This project is provided as-is for educational and commercial use. Daraz Seller Pro is not affiliated with Daraz.com or its parent company.

## 🤝 Contributing

While this is a standalone tool, feedback and suggestions are always welcome for improving the calculator's accuracy and features.

---

**Happy Selling! 🚀**

*Calculate with confidence, sell with success*
