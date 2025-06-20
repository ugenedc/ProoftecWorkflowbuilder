# ProofTec Workflow Builder

A clean, minimalist workflow management system for vehicle inspection processes. Built with vanilla HTML, CSS, and JavaScript with a focus on elegant design and user experience.

## 🚀 Live Demo

Visit the live application: [ProofTec Workflow Builder](https://ugenedc.github.io/ProoftecWorkflowbuilder/)

## ✨ Features

### 🎯 **Clean Minimalist Design**
- Modern, professional interface with subtle rounded corners
- Elegant color palette and typography
- Responsive design that works on all devices

### 🔧 **Workflow Management**
- **Create Custom Workflows**: Build inspection workflows with drag-and-drop components
- **Save & Load**: Persistent storage of workflows using localStorage
- **Component Categories**: Organized inspection steps including:
  - Vehicle Information (Customer details, VIN, License plate, etc.)
  - Exterior Views (Front, sides, rear, roof scans)
  - Wheels & Tires (All wheel inspections)
  - Interior (Dashboard, seats, console)
  - Storage Areas (Glove box, trunk, door pockets)
  - Engine & Mechanical (Engine bay, undercarriage, exhaust)
  - Lights & Electronics (Headlights, taillights, indicators)
  - Damage Documentation (Scratch/dent assessment, paint condition)
  - Process Steps (Final inspection, customer sign-off, reporting)

### 🎨 **Custom Components**
- **Custom Text Fields**: Add custom labels and instructions
- **Custom Notes**: Detailed inspector notes and multi-line text
- **Custom Checkboxes**: Yes/no verification points
- **Custom Photo Points**: Specific photo capture requirements
- **Editable Content**: Modal-based editing with professional forms

### 🔄 **Drag & Drop Interface**
- Intuitive component management
- Reorder workflow steps easily
- Visual feedback during interactions

### 📱 **Modern UI Elements**
- **Feather Icons**: Clean, minimalist line-style icons
- **Collapsible Sections**: Organized component categories
- **Professional Modals**: Beautiful forms with proper validation
- **Hover Effects**: Subtle, elegant interactions

## 🛠 Technology Stack

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Icons**: Feather Icons library
- **Storage**: Browser localStorage for data persistence
- **Hosting**: GitHub Pages

## 📋 Getting Started

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ugenedc/ProoftecWorkflowbuilder.git
   cd ProoftecWorkflowbuilder
   ```

2. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. **Start building workflows**:
   - Navigate to the workflow editor
   - Drag components from the sidebar to build your inspection workflow
   - Save and load workflows as needed

## 📁 Project Structure

```
ProoftecWorkflowbuilder/
├── index.html              # Main workflow list page
├── workflow-editor.html    # Workflow builder interface
└── README.md              # Project documentation
```

## 🎮 Usage

### Creating a Workflow
1. Click "Create New Workflow" from the main page
2. Enter workflow name and description
3. Drag components from the sidebar to the workflow area
4. Customize components by clicking the edit button
5. Save your workflow

### Loading a Workflow
1. Click "Load Workflow" in the editor
2. Select from existing workflows
3. Edit and modify as needed

### Customizing Components
- Click the edit button (✏️) on custom components
- Fill in specific details in the modal
- Save changes to update the workflow

## 🎨 Design Philosophy

This project emphasizes:
- **Minimalism**: Clean, uncluttered interface
- **Usability**: Intuitive drag-and-drop interactions
- **Professionalism**: Enterprise-ready design language
- **Accessibility**: Proper focus states and keyboard navigation
- **Performance**: Lightweight, fast-loading application

## 🔧 Browser Support

- **Chrome**: ✅ Fully supported
- **Firefox**: ✅ Fully supported  
- **Safari**: ✅ Fully supported
- **Edge**: ✅ Fully supported

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

For support or questions, please open an issue on GitHub.

---

Built with ❤️ for modern vehicle inspection workflows 