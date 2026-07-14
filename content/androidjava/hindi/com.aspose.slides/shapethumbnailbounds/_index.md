---
title: ShapeThumbnailBounds
second_title: Aspose.Slides Android के लिए Java API संदर्भ द्वारा
description: shape thumbnail bounds के प्रकारों का enumeration।
type: docs
url: /hi/com.aspose.slides/shapethumbnailbounds/
---
**विरासत:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

shape thumbnail bounds के प्रकारों का enumeration.
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Slide](#Slide) | Shape thumbnail का आकार slide size के बराबर होगा। |
| [Shape](#Shape) | Shape thumbnail का आकार shape bounds rectangle के बराबर होगा, जिसमें shape outline settings को ध्यान में रखा गया है। |
| [Appearance](#Appearance) | Shape thumbnail का आकार shape appearance के बराबर होगा (स्लाइड की सीमाओं के भीतर)। |
### Slide {#Slide}
```
public static final int Slide
```

Shape thumbnail का आकार slide size के बराबर होगा। Shape position सहेजा जाएगा।

### Shape {#Shape}
```
public static final int Shape
```

Shape thumbnail का आकार shape bounds rectangle के बराबर होगा, जिसमें shape outline settings को ध्यान में रखा गया है।

### Appearance {#Appearance}
```
public static final int Appearance
```

Shape thumbnail का आकार shape appearance के बराबर होगा (स्लाइड की सीमाओं के भीतर)। ऐसे मामले हो सकते हैं जब shape appearance shape bounds में फिट नहीं होता। E.g. rotation, miter join of acute angle , 3D effects, आदि.