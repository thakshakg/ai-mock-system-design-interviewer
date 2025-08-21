# 🧠 AI System Design Mock Interviewer

An intelligent mock interviewer designed to help candidates prepare for system design interviews. This project simulates realistic interview scenarios, provides feedback, and guides users through architectural decision-making. The application features an integrated whiteboard for diagramming and a chat interface for interacting with the AI interviewer.

## 🚀 Core Components

The application is divided into two main areas: the AI Interviewer chat and the interactive Whiteboard. The layout is a split-screen view that is resizable to suit your workflow.

### 1. AI System Design Interviewer

The chat interface allows you to engage in a mock system design interview with an AI.

**Features:**
- **Realistic Interview Flow:** The AI guides you through the standard stages of a system design interview:
  - Requirements Clarification
  - High-Level Design
  - Deep Dive
  - Scaling & Bottlenecks
  - Closing
- **Dynamic Questions:** The AI asks relevant follow-up questions based on your responses.
- **Pre-set Scenarios:** You can choose from a dropdown list of common system design questions (e.g., "Design a URL shortener," "Design a social media feed").
- **Integrated Feedback:** After the interview, the AI can provide a detailed evaluation of your performance.

### 2. Interactive Whiteboard

The whiteboard is a powerful tool for visual thinking and diagramming your system architecture.

**Drawing Tools:**
- **Pencil:** For freehand sketching.
- **Shapes:** Draw `Lines`, `Arrows`, `Rectangles`, and `Circles`.
- **Text:** Add text annotations to your diagrams.
- **Delete:** Remove individual objects from the canvas.
- **Clear:** Wipe the entire canvas clean (with a confirmation to prevent accidents).

**Controls & Customization:**
- **Color Picker:** Change the color of any tool or selected object.
- **Size Slider:** Adjust the stroke width for shapes and the font size for text.
  - *Smart Sizing:* The app remembers your size preference for each individual tool.
- **Font Selector:** Choose from a variety of fonts for your text objects. This control appears when the text tool is active.

**Integration with Chat:**
- **Send Snapshots:** Your whiteboard diagrams can be sent to the AI interviewer as part of your message, allowing you to visually explain your design.

## How to Use

1. **Select a Question:** Choose a system design problem from the dropdown menu at the top of the chat area.
2. **Start the Interview:** The AI will begin the interview. Use the chat input to type your responses.
3. **Use the Whiteboard:** Use the tools on the left to draw your architecture. You can customize the color, size, and font of your drawings.
4. **Send Your Design:** When you want to share your diagram, simply type your message and click "Send." A snapshot of your whiteboard will be included with your message.
5. **Iterate and Improve:** Work through the interview stages with the AI, refining your design based on its questions and feedback.
