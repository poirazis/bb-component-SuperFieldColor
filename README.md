# Super Field - Color

An intuitive color picker component for Budibase applications with theme integration, custom color support, and flexible display options.

## 🚀 Features

### Color Selection

- **Theme Colors**: Pre-defined color palette matching your application theme
- **Static Colors**: Standard web color options
- **Custom Colors**: User-defined color palette
- **Manual Input**: Direct hex/rgb color value entry
- **Visual Picker**: Interactive color selection interface

### Display Options

- **Swatch Styles**: Square or circular color swatches
- **Field Binding**: String field for storing color values
- **Default Values**: Pre-selected default colors
- **Help Text**: Guidance for color selection

### Validation & Control

- **Color Validation**: Hex, rgb, and named color validation
- **Input Masking**: Format restrictions for color values
- **Event Handling**: On change events with color context
- **State Management**: Disabled and readonly modes

### User Experience

- **Intuitive Interface**: Visual color picker with preview
- **Accessibility**: Keyboard navigation and screen reader support
- **Responsive Design**: Adapts to different screen sizes
- **Performance**: Efficient color rendering and selection

### Styling & Layout

- **Flexible Positioning**: Label placement options
- **Field Modes**: Form input or inline editing
- **Size Configuration**: Adjustable component width
- **Theme Integration**: Consistent with Budibase design system

## 📝 Usage Instructions

### Basic Setup

1. Add the Super Field - Color component to your form
2. Bind to a string field for storing color values
3. Configure color palette options (theme, static, custom)
4. Set default color value if needed

### Advanced Configuration

- **Color Palettes**: Enable theme colors for brand consistency
- **Custom Options**: Add specific colors for your use case
- **Input Control**: Allow or restrict manual color entry
- **Display Style**: Choose square or circular swatches

### Common Use Cases

- **Theme Customization**: User-selected application colors
- **Brand Colors**: Consistent color selection across forms
- **Data Visualization**: Color coding for charts and categories
- **Design Tools**: Color picker for design applications
- **Status Indicators**: Color-coded status or priority levels

## 🔧 Configuration Options

| Setting        | Type    | Description                   |
| -------------- | ------- | ----------------------------- |
| Field          | String  | Color value field binding     |
| Label          | String  | Display label text            |
| Default Value  | String  | Pre-selected color value      |
| Help Text      | String  | Help/instruction text         |
| Validation     | Rules   | Color format validation       |
| Theme Colors   | Boolean | Enable theme color palette    |
| Static Colors  | Boolean | Enable standard color options |
| Custom Colors  | Options | User-defined color palette    |
| Allow Input    | Boolean | Enable manual color entry     |
| Disabled       | Boolean | Disable color selection       |
| Read Only      | Boolean | Read-only mode                |
| Mode           | Select  | Form or inline input style    |
| Label Position | Select  | Label placement               |
| Size           | Number  | Component width span          |
| Swatch         | Select  | Square or circular display    |

## 📋 Events

### On Change

Triggered when a color is selected or changed.

**Context:**

- `value`: The selected color value (hex/rgb/name)
- `field`: The bound field information

## 🎨 Styling

Integrates with Budibase's styling system:

- **Color Preview**: Live color swatch display
- **Theme Consistency**: Matches application color scheme
- **Custom CSS**: Advanced styling options
- **Responsive**: Mobile-optimized color picker

## 🔍 Best Practices

- Enable theme colors for consistent branding
- Use custom colors for specific business requirements
- Consider accessibility with sufficient color contrast
- Provide help text for color meaning/significance
- Test color picker on mobile devices
- Validate color formats for data integrity
