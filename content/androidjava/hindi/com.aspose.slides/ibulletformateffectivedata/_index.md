---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: एक अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी पैराग्राफ बुलेट फ़ॉर्मेटिंग गुणों को समाहित करता है।
type: docs
url: /hi/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

एक अपरिवर्तनीय ऑब्जेक्ट जो प्रभावी पैराग्राफ बुलेट फ़ॉर्मेटिंग गुणों को समाहित करता है।

--------------------

यह इंटरफ़ेस [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) का एक भाग है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getType()](#getType--) | एक पैराग्राफ का बुलेट प्रकार लौटाता है। |
| [getChar()](#getChar--) | एक पैराग्राफ का बुलेट कैरक्टर लौटाता है। |
| [getActualBulletValue()](#getActualBulletValue--) | पैरेंट पैराग्राफ के लिए वास्तविक बुलेट मान लौटाता है। |
| [getFont()](#getFont--) | एक पैराग्राफ का बुलेट फ़ॉन्ट लौटाता है। |
| [getHeight()](#getHeight--) | एक पैराग्राफ का बुलेट ऊँचाई लौटाता है। |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | क्रमांकित बुलेट समूह के लिए उपयोग किया जाने वाला पहला नंबर लौटाता है। |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | क्रमांकित बुलेट की शैली लौटाता है। |
| [isBulletHardColor()](#isBulletHardColor--) | निर्धारित करता है कि बुलेट का अपना रंग है या वह पैराग्राफ के पहले भाग से विरासत में मिलता है। |
| [isBulletHardFont()](#isBulletHardFont--) | निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या वह पैराग्राफ के पहले भाग से विरासत में मिलता है। |
| [getPicture()](#getPicture--) | पैराग्राफ में बुलेट के रूप में उपयोग की गई तस्वीर लौटाता है। |
| [getFillFormat()](#getFillFormat--) | पैराग्राफ का बुलेट फ़िल फ़ॉर्मेट लौटाता है। |

### getType() {#getType--}
```
public abstract byte getType()
```

एक पैराग्राफ का बुलेट प्रकार लौटाता है। केवल-पढ़ने योग्य [BulletType](../../com.aspose.slides/bullettype)।

**रिटर्न:**  
byte

### getChar() {#getChar--}
```
public abstract char getChar()
```

एक पैराग्राफ का बुलेट कैरक्टर लौटाता है। केवल-पढ़ने योग्य char।

**रिटर्न:**  
char

### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

पैरेंट पैराग्राफ के लिए वास्तविक बुलेट मान लौटाता है। केवल-पढ़ने योग्य String।

**रिटर्न:**  
java.lang.String

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

एक पैराग्राफ का बुलेट फ़ॉन्ट लौटाता है। केवल-पढ़ने योग्य [IFontData](../../com.aspose.slides/ifontdata)।

**रिटर्न:**  
[IFontData](../../com.aspose.slides/ifontdata)

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

एक पैराग्राफ का बुलेट ऊँचाई लौटाता है। केवल-पढ़ने योग्य float।

**रिटर्न:**  
float

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

क्रमांकित बुलेट समूह के लिए उपयोग किया जाने वाला पहला नंबर लौटाता है। केवल-पढ़ने योग्य short।

**रिटर्न:**  
short

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

क्रमांकित बुलेट की शैली लौटाता है। केवल-पढ़ने योग्य [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)।

**रिटर्न:**  
byte

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

निर्धारित करता है कि बुलेट का अपना रंग है या वह पैराग्राफ के पहले भाग से विरासत में मिलता है। यदि बुलेट का अपना रंग है तो **true** और यदि बुलेट पैराग्राफ के पहले भाग से रंग विरासत में लेता है तो **false** लौटाता है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

निर्धारित करता है कि बुलेट का अपना फ़ॉन्ट है या वह पैराग्राफ के पहले भाग से विरासत में मिलता है। यदि बुलेट का अपना फ़ॉन्ट है तो **true** और यदि बुलेट पैराग्राफ के पहले भाग से फ़ॉन्ट विरासत में लेता है तो **true** लौटाता है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean

### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

पैराग्राफ में बुलेट के रूप में उपयोग की गई तस्वीर लौटाता है। केवल-पढ़ने योग्य [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)।

**रिटर्न:**  
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

एक पैराग्राफ का बुलेट फ़िल फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)।

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // मान लें कि पहली स्लाइड में पहला आकार AutoShape है जिसमें कुछ पाठ है...
>      // टेक्स्ट पैराग्राफ़ के बुलेट्स की जानकारी आउटपुट करें
>      AutoShape autoShape = (AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for (IParagraph para : autoShape.getTextFrame().getParagraphs())
>      {
>          IBulletFormatEffectiveData bulletFormatEffective = para.getParagraphFormat().getBullet().getEffective();
>          System.out.println("Bullet type: " + bulletFormatEffective.getType());
>          if (bulletFormatEffective.getType() != BulletType.None)
>          {
>              System.out.println("Bullet fill type: " + bulletFormatEffective.getFillFormat().getFillType());
>              switch (bulletFormatEffective.getFillFormat().getFillType())
>              {
>                  case FillType.Solid:
>                      System.out.println("Solid fill color: " + bulletFormatEffective.getFillFormat().getSolidFillColor());
>                      break;
>                  case FillType.Gradient:
>                      System.out.println("Gradient stops count: " + bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops().size());
>                      for (IGradientStopEffectiveData gradStop : bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops())
>                          System.out.println(gradStop.getPosition() + ": " + gradStop.getColor());
>                      break;
>                  case FillType.Pattern:
>                      System.out.println("Pattern style: " + bulletFormatEffective.getFillFormat().getPatternFormat().getPatternStyle());
>                      System.out.println("Fore color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getForeColor());
>                      System.out.println("Back color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getBackColor());
>                      break;
>              }
>          }
>          System.out.println();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)