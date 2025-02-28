```markdown:README.md
# QCM - Interactive Quiz Application

A modern, interactive quiz application built with Next.js, TypeScript, and Tailwind CSS. This application allows users to test their knowledge across various subjects with features like learning mode and exam mode.

## Features

- 🎯 Multiple quiz themes/subjects
- 📚 Two learning modes:
  - Learning Mode: Shows correct answers and explanations
  - Exam Mode: Simulates test conditions
- 🔄 Randomized questions and answers
- ⏮️ Navigation between questions
- 📊 Detailed results summary
- 📱 Responsive design
- 🎨 Modern UI with Tailwind CSS
- 🌐 Built with Next.js and TypeScript

## Tech Stack

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Radix UI](https://www.radix-ui.com/)
- [Lucide Icons](https://lucide.dev/)

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/qcm.git
```

2. Navigate to the project directory:
```bash
cd qcm
```

3. Install dependencies:
```bash
npm install
# or
yarn install
```

4. Run the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Project Structure

```
qcm/
├── app/
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── Question.tsx
│   ├── Quiz.tsx
│   ├── Results.tsx
│   ├── Summary.tsx
│   └── ThemeSelector.tsx
├── lib/
│   └── utils.ts
├── public/
│   └── question.ts
└── ...
```

## Features in Detail

### Quiz Modes

1. **Learning Mode**
   - Shows correct answers after each question
   - Allows reviewing previous questions
   - Provides immediate feedback

2. **Exam Mode**
   - Simulates real exam conditions
   - No immediate feedback
   - Final score at completion

### Question Navigation

- Skip questions
- Return to previous questions
- Track progress with question counter

### Results

- Detailed score summary
- Percentage calculation
- Review of correct and incorrect answers
- Option to restart quiz

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) for the styling
- [Next.js](https://nextjs.org/) for the framework
- [Radix UI](https://www.radix-ui.com/) for UI components

## Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter)

Project Link: [https://github.com/yourusername/qcm](https://github.com/yourusername/qcm)
```

This README provides a comprehensive overview of your project, including:
- Features and functionality
- Technology stack
- Installation instructions
- Project structure
- Detailed feature explanations
- Contributing guidelines
- License information
- Contact details

Remember to:
1. Replace `yourusername` with your actual GitHub username
2. Add your social media links
3. Update the license section if you're using a different license
4. Add or modify sections based on your specific project needs
5. Add any additional setup instructions if needed
