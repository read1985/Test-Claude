# Personal Finance Dashboard

A comprehensive web-based personal finance management application that helps users track their financial transactions, categorize expenses, and gain insights into their spending patterns.

## Features

### 📊 **Financial Overview**
- Real-time balance tracking
- Monthly income and expense summaries
- Visual spending charts and trends
- Transactions requiring review alerts

### 💳 **Transaction Management**
- Add and track financial transactions
- Search and filter transactions
- Export transaction data to CSV
- Automatic categorization with custom rules

### 🏷️ **Category Management**
- Create custom expense and income categories
- Visual category breakdown with pie charts
- Color-coded category system
- Track spending by category

### 🤖 **Automation Rules**
- Create rules to automatically categorize transactions
- Pattern matching based on transaction descriptions
- Confidence-based categorization system
- Bulk categorization application

### 📈 **Financial Insights**
- Monthly spending trends
- Top spending categories analysis
- Interactive charts and visualizations
- Historical financial data tracking

### 🔐 **User Authentication**
- Secure user registration and login
- Demo account for testing
- Personal data isolation
- Secure session management

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js for data visualization
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Supabase Auth
- **Deployment**: Vercel
- **Icons**: Font Awesome

## Database Schema

The application uses the following main tables:
- `transactions` - Financial transaction records
- `categories` - User-defined expense/income categories
- `rules` - Automation rules for transaction categorization

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/read1985/Test-Claude.git
   cd Test-Claude
   ```

2. **Configure Supabase**
   - Create a new Supabase project
   - Copy `.env.example` to `.env`
   - Update the environment variables with your Supabase credentials:
     ```
     VITE_SUPABASE_URL=your-supabase-url
     VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
     ```

3. **Deploy to Vercel**
   - Connect your GitHub repository to Vercel
   - Add environment variables in Vercel dashboard
   - Deploy automatically on git push

## Usage

1. **Sign Up/Sign In**: Create an account or use the demo account
2. **Add Categories**: Create categories for organizing transactions
3. **Add Transactions**: Record income and expenses
4. **Create Rules**: Set up automation rules for categorization
5. **View Insights**: Analyze spending patterns and trends

## Demo

A live demo is available at: [https://test-claude-coral.vercel.app](https://test-claude-coral.vercel.app)

Use the "Demo with Test Account" option to explore the features without creating an account.

## Security Features

- Row Level Security (RLS) enabled on all tables
- Secure HTTP headers configuration
- XSS protection
- Content security policies
- User data isolation

## Browser Support

- Modern browsers with ES6+ support
- Chrome, Firefox, Safari, Edge
- Mobile-responsive design

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the MIT License.