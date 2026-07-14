---
title: TextStyle
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: यह वर्ग टेक्स्ट शैली स्वरूपण गुणों को सम्मिलित करता है।
type: docs
url: /hi/com.aspose.slides/textstyle/
---
**वंशानुक्रम:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

यह वर्ग टेक्स्ट शैली स्वरूपण गुणों को सम्मिलित करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | यदि शैली का स्तर मौजूद है तो उसे लौटाता है, अन्यथा null लौटाता है। |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | डिफ़ॉल्ट पैराग्राफ गुण। |
| [getEffective()](#getEffective--) | विरासत लागू होकर प्रभावी टेक्स्ट शैली स्वरूपण डेटा प्राप्त करता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long.

**वापसी:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```

यदि शैली का स्तर मौजूद है तो उसे लौटाता है, अन्यथा null लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित सूचकांक स्तर का। 0..8 अंतराल में होना चाहिए। |

**वापसी:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - स्तर [IParagraphFormat](../../com.aspose.slides/iparagraphformat) का स्वरूपण।
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```

डिफ़ॉल्ट पैराग्राफ गुण। केवल-पढ़ने योग्य [IParagraphFormat](../../com.aspose.slides/iparagraphformat)।

**वापसी:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```

विरासत लागू होकर प्रभावी टेक्स्ट शैली स्वरूपण डेटा प्राप्त करता है।

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - एक [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).