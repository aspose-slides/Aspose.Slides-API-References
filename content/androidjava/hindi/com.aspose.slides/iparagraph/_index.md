---
title: IParagraph
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: एक पाठ के अनुच्छेद का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iparagraph/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

पाठ का एक पैराग्राफ दर्शाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getPortions()](#getPortions--) | टेक्स्ट हिस्सों का संग्रह लौटाता है। |
| [getParagraphFormat()](#getParagraphFormat--) | इस पैराग्राफ के फ़ॉर्मेटिंग ऑब्जेक्ट को लौटाता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [getText()](#getText--) | पैराग्राफ का सादा पाठ प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | पैराग्राफ का सादा पाठ प्राप्त करता है या सेट करता है। |
| [getRect()](#getRect--) | पैराग्राफ को सीमांकन करने वाले आयत के निर्देशांक प्राप्त करता है। |
| [getLinesCount()](#getLinesCount--) | पैराग्राफ में लाइनों की संख्या प्राप्त करता है। |
| [getImage()](#getImage--) | पैराग्राफ की छवि लौटाता है। |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | निर्दिष्ट स्केल के साथ पैराग्राफ की छवि लौटाता है। |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | यदि अंतिम हिस्से के बाद एक नया हिस्सा डाला जाता है तो उपयोग की जाने वाली हिस्सा गुण निर्दिष्ट करता है। |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | यदि अंतिम हिस्से के बाद एक नया हिस्सा डाला जाता है तो उपयोग की जाने वाली हिस्सा गुण निर्दिष्ट करता है। |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


टेक्स्ट हिस्सों का संग्रह लौटाता है। केवल-पढ़ने-योग्य [IPortionCollection](../../com.aspose.slides/iportioncollection)।

**वापसी:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


इस पैराग्राफ के फ़ॉर्मेटिंग ऑब्जेक्ट को लौटाता है। केवल-पढ़ने-योग्य [IParagraphFormat](../../com.aspose.slides/iparagraphformat)।

**वापसी:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


समान फ़ॉर्मेटिंग वाले रन को जोड़ता है।

### getText() {#getText--}
```
public abstract String getText()
```


पैराग्राफ का सादा पाठ प्राप्त करता है या सेट करता है। पढ़ने/लिखने-योग्य स्ट्रिंग।

मान: पाठ।

**वापसी:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


पैराग्राफ का सादा पाठ प्राप्त करता है या सेट करता है। पढ़ने/लिखने-योग्य स्ट्रिंग।

मान: पाठ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```


पैराग्राफ को सीमांकन करने वाले आयत के निर्देशांक प्राप्त करता है। आयत में पैराग्राफ की सभी पंक्तियों का पाठ शामिल है, जिसमें खाली पंक्तियाँ भी शामिल हैं।

**वापसी:**
android.graphics.RectF - Rectangle that bounds paragraph android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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
int - Lines count in a paragraph
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


पैराग्राफ की छवि लौटाता है।

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
[IImage](../../com.aspose.slides/iimage) - An image containing the rendered paragraph, or null if the paragraph cannot be found in its parent collection, has no valid rendering bounds, or an error occurs while rendering the image.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```


निर्दिष्ट स्केल के साथ पैराग्राफ की छवि लौटाता है।

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleX | float | पैराग्राफ छवि पर लागू किया गया क्षैतिज स्केल फैक्टर। |
| scaleY | float | पैराग्राफ छवि पर लागू किया गया ऊर्ध्वाधर स्केल फैक्टर। |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - An image containing the rendered paragraph, or null if the paragraph cannot be found in its parent collection, has no valid rendering bounds, or an error occurs while rendering the image.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


यदि अंतिम हिस्से के बाद एक नया हिस्सा डाला जाता है तो उपयोग की जाने वाली हिस्सा गुण निर्दिष्ट करता है।

**वापसी:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


यदि अंतिम हिस्से के बाद एक नया हिस्सा डाला जाता है तो उपयोग की जाने वाली हिस्सा गुण निर्दिष्ट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |