# Moshino - Concert Booking Platform

A modern ASP.NET Core Razor Pages application for concert ticket booking, converted from the original HTML design.

## 🎵 Features

- **Responsive Design**: Mobile-first design with Tailwind CSS
- **Modern UI**: Dark theme with purple gradient accents
- **Component-Based**: Organized with partial views for reusability
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Cross-Platform**: Built with .NET 8

## 🚀 Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- A code editor (Visual Studio, VS Code, or Rider)

### Running the Application

1. **Clone or navigate to the project directory**
   ```bash
   cd /workspace
   ```

2. **Restore dependencies**
   ```bash
   dotnet restore
   ```

3. **Run the application**
   ```bash
   dotnet run
   ```

4. **Open your browser** and navigate to:
   - HTTP: `http://localhost:5000`
   - HTTPS: `https://localhost:7000`

## 📁 Project Structure

```
Moshino/
├── Pages/
│   ├── Shared/
│   │   ├── _Layout.cshtml          # Main layout template
│   │   ├── _Navigation.cshtml      # Header and navigation component
│   │   ├── _Footer.cshtml          # Footer component
│   │   └── _SponsorsSection.cshtml # Sponsors section component
│   ├── Index.cshtml                # Home page
│   ├── Index.cshtml.cs             # Home page code-behind
│   ├── Error.cshtml                # Error page
│   ├── Error.cshtml.cs             # Error page code-behind
│   ├── _ViewStart.cshtml           # Sets default layout
│   └── _ViewImports.cshtml         # Global imports and namespaces
├── Properties/
│   └── launchSettings.json         # Development server settings
├── wwwroot/
│   ├── css/
│   │   └── site.css                # Custom styles and gradients
│   └── js/
│       └── site.js                 # Mobile menu functionality
├── appsettings.json                # Application configuration
├── appsettings.Development.json    # Development configuration
├── Moshino.csproj                  # Project file
├── Program.cs                      # Application entry point
└── README.md                       # This file
```

## 🎨 Design System

### Colors
- **Background**: Very dark gray (`#0c0a09`)
- **Text**: Light gray (`#e2e8f0`)
- **Accent**: Purple to indigo gradient
- **Secondary**: Slate colors for navigation and footer

### Typography
- **Font**: Inter (Google Fonts)
- **Headings**: Bold and extrabold weights
- **Body**: Regular weight with good readability

### Components
- **Navigation**: Responsive with mobile hamburger menu
- **Buttons**: Gradient backgrounds with hover effects
- **Cards**: Rounded corners with shadow effects
- **Footer**: Multi-column layout with social links

## 🔧 Key Features Implemented

1. **Responsive Navigation**
   - Desktop horizontal navigation
   - Mobile hamburger menu
   - Smooth transitions

2. **Hero Section**
   - Large typography with gradient text
   - Placeholder image with error handling
   - Centered layout

3. **Sponsors Section**
   - Brand logos with Font Awesome icons
   - Responsive grid layout
   - Subtle opacity for visual hierarchy

4. **Footer**
   - Multi-column links
   - Social media icons
   - Copyright notice

## 🛠️ Development

### Adding New Pages

1. Create a new `.cshtml` file in the `Pages` directory
2. Add corresponding `.cshtml.cs` code-behind file
3. Use `@page` directive at the top
4. Follow the existing structure and styling

### Customizing Styles

- Modify `wwwroot/css/site.css` for custom styles
- The project uses Tailwind CSS via CDN
- Custom gradients and colors are defined in the CSS file

### JavaScript Functionality

- Mobile menu toggle is implemented in `wwwroot/js/site.js`
- Additional JavaScript can be added to this file or as separate files

## 📱 Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive design works on all screen sizes

## 🚀 Deployment

The application is ready for deployment to:
- Azure App Service
- IIS
- Docker containers
- Any .NET 8 compatible hosting platform

## 📝 License

This project is created for demonstration purposes.

---

**Note**: This is a conversion of an HTML template to ASP.NET Core Razor Pages, maintaining the original design and functionality while adding the benefits of a server-side framework.