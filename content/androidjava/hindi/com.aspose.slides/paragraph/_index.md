---
title: Paragraph
second_title: Aspose.Slides for Android Java API संदर्भ के माध्यम से
description: टेक्स्ट के एक पैराग्राफ का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/paragraph/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

टेक्स्ट का एक पैराग्राफ दर्शाता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [Paragraph()](#Paragraph--) | Paragraph क्लास का एक नया उदाहरण डिफ़ॉल्ट प्रॉपर्टीज़ के साथ प्रारंभ करता है। |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | कॉपी कंस्ट्रक्टर जो Paragraph क्लास का एक नया उदाहरण प्रारंभ करता है। |

## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getPortions()](#getPortions--) | टेक्स्ट भागों का संग्रह लौटाता है। |
| [getParagraphFormat()](#getParagraphFormat--) | इस पैराग्राफ के लिए फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | एक ही फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [getText()](#getText--) | पैराग्राफ का प्लेन टेक्स्ट प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | पैराग्राफ का प्लेन टेक्स्ट प्राप्त करता है या सेट करता है। |
| [getRect()](#getRect--) | पैराग्राफ को सीमित करने वाले रेक्ट के निर्देशांक प्राप्त करता है। |
| [getLinesCount()](#getLinesCount--) | पैराग्राफ में लाइनों की संख्या प्राप्त करता है। |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | यदि अंतिम भाग के बाद दूसरा भाग डाला जाता है तो उपयोग होने वाली भाग प्रॉपर्टीज़ निर्दिष्ट करता है। |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | यदि अंतिम भाग के बाद दूसरा भाग डाला जाता है तो उपयोग होने वाली भाग प्रॉपर्टीज़ निर्दिष्ट करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | पैराग्राफ का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | पैराग्राफ का पैरेंट प्रेज़ेंटेशन लौटाता है। |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Paragraph क्लास का एक नया उदाहरण डिफ़ॉल्ट प्रॉपर्टीज़ के साथ प्रारंभ करता है।

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

कॉपी कंस्ट्रक्टर जो Paragraph क्लास का एक नया उदाहरण प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

टेक्स्ट भागों का संग्रह लौटाता है। केवल पढ़ने योग्य [IPortionCollection](../../com.aspose.slides/iportioncollection)।

**वापसी:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

इस पैराग्राफ के लिए फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IParagraphFormat](../../com.aspose.slides/iparagraphformat)।

--------------------

फ़ॉर्मेटिंग ऑब्जेक्ट केवल वर्तमान पैराग्राफ के लिए परिभाषित फ़ॉर्मेटिंग पैरामीटर रखता है, विरासत में मिली डेटा लागू नहीं होती।

विरासत में मिली मानों सहित प्रभावी मान प्राप्त करने के लिए [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) मेथड का उपयोग करें।

**वापसी:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

एक ही फ़ॉर्मेटिंग वाले रन को जोड़ता है।

### getText() {#getText--}
```
public final String getText()
```

पैराग्राफ का प्लेन टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य स्ट्रिंग।

मान: टेक्स्ट।

**वापसी:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

पैराग्राफ का प्लेन टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य स्ट्रिंग।

मान: टेक्स्ट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

पैराग्राफ को सीमित करने वाले रेक्ट के निर्देशांक प्राप्त करता है। रेक्ट में पैराग्राफ की सभी पाठ लाइनों, खाली लाइनों सहित, शामिल हैं।

**वापसी:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

पैराग्राफ में लाइनों की संख्या प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
int - पैराग्राफ में लाइनों की गिनती
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

यदि अंतिम भाग के बाद दूसरा भाग डाला जाता है तो उपयोग होने वाली भाग प्रॉपर्टीज़ निर्दिष्ट करता है।

**वापसी:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

यदि अंतिम भाग के बाद दूसरा भाग डाला जाता है तो उपयोग होने वाली भाग प्रॉपर्टीज़ निर्दिष्ट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

पैराग्राफ का पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

पैराग्राफ का पैरेंट प्रेज़ेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)