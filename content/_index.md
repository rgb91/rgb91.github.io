---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Resume_Sanjay_Saha.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research explores the intersection of computer vision, multimodal content understanding and biometric security. During my PhD at the National University of Singapore, I developed algorithms to assess AI-generated content (AIGC) while also conducting interdisciplinary studies on how manipulated media impacts audience perception and digital literacy. 
        
        My academic works published in top-tier venues like ICCV, KDD, and Pattern Recognition, are deeply driven by practical, real-life AI/ML challenges. At TikTok, I translate these foundational research ideas into production-scale multimodal AI systems, designing robust computer vision and retrieval pipelines to safeguard high-volume livestreaming environments.

        Feel free reach out to collaborate 😃
    design:
      columns: '1'
  - block: markdown
    content:
      title: '🧑‍🎓 My Teaching'
      subtitle: ''
      text: |-
        I've spent over eight years teaching across multiple universities, and I'm deeply passionate about making complex technical subjects accessible and engaging. My teaching journey has taken me through roles as an Assistant Professor, Lecturer at UIU and UAP (Dhaka), and Graduate Teaching Assistant at the National University of Singapore (NUS). 
        
        Along the way, I've taught a wide variety of classes, everything from foundational algorithms and programming to advanced applied machine learning. I really enjoy breaking down advanced AI concepts for inter-disciplinary cohorts, making sure students from all backgrounds feel confident tackling the material. I also place a heavy emphasis on personalized mentorship, and one of my favorite experiences has been guiding undergraduate research groups through to their first peer-reviewed publications. 
    design:
      columns: '1'
---
