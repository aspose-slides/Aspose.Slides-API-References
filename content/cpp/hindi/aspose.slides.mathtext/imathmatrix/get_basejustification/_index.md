---
title: get_BaseJustification()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "आसपास के पाठ के सापेक्ष ऊर्ध्वाधर संरेखण को निर्दिष्ट करता है। संभावित मान हैं top, bottom, और center। डिफ़ॉल्ट: Center"
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() method


आसपास के पाठ के सापेक्ष ऊर्ध्वाधर संरेखण को निर्दिष्ट करता है। संभावित मान हैं top, bottom, और center। डिफ़ॉल्ट: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## संबंधित देखें

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* क्लास [IMathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)