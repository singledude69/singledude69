- 👋 Hi, I’m @singledude69
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
singledude69/singledude69 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->from pptx import Presentation

# Create a new PowerPoint presentation
presentation = Presentation()

# Slide 1 - Title slide
slide_1 = presentation.slides.add_slide(presentation.slide_layouts[0])
title = slide_1.shapes.title
subtitle = slide_1.placeholders[1]
title.text = "Motion"
subtitle.text = "Chapter Presentation"

# Slide 2 - Definition of motion
slide_2 = presentation.slides.add_slide(presentation.slide_layouts[1])
title = slide_2.shapes.title
content = slide_2.placeholders[1]
title.text = "Definition of Motion"
content.text = "Motion is the change in position of an object with respect to its surroundings."

# Slide 3 - Types of motion
slide_3 = presentation.slides.add_slide(presentation.slide_layouts[1])
title = slide_3.shapes.title
content = slide_3.placeholders[1]
title.text = "Types of Motion"
content.text = "1. Linear Motion\n2. Circular Motion\n3. Oscillatory Motion\n4. Random Motion"

# Slide 4 - Linear motion
slide_4 = presentation.slides.add_slide(presentation.slide_layouts[2])
title = slide_4.shapes.title
content = slide_4.placeholders[1]
title.text = "Linear Motion"
content.text = "Linear motion is the motion in a straight line."

# Slide 5 - Circular motion
slide_5 = presentation.slides.add_slide(presentation.slide_layouts[2])
title = slide_5.shapes.title
content = slide_5.placeholders[1]
title.text = "Circular Motion"
content.text = "Circular motion is the motion along a circular path."

# Slide 6 - Oscillatory motion
slide_6 = presentation.slides.add_slide(presentation.slide_layouts[2])
title = slide_6.shapes.title
content = slide_6.placeholders[1]
title.text = "Oscillatory Motion"
content.text = "Oscillatory motion is the motion of an object back and forth around a central position."

# Slide 7 - Random motion
slide_7 = presentation.slides.add_slide(presentation.slide_layouts[2])
title = slide_7.shapes.title
content = slide_7.placeholders[1]
title.text = "Random Motion"
content.text = "Random motion is the motion that lacks any specific pattern or direction."

# Save the presentation
presentation.save("motion_chapter.pptx")


