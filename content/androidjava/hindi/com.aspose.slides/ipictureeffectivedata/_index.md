---
title: IPictureEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: अपरिवर्तनीय ऑब्जेक्ट जिसमें प्रभावी चित्र गुण होते हैं।
type: docs
url: /hi/com.aspose.slides/ipictureeffectivedata/
---```
public interface IPictureEffectiveData
```

अपरिवर्तनीय ऑब्जेक्ट जिसमें प्रभावी चित्र गुण होते हैं।

--------------------

यह इंटरफ़ेस [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata) और [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) के एक भाग के रूप में उपयोग किया जाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getImage()](#getImage--) | एंबेडेड छवि लौटाता है। |
| [getLinkPathLong()](#getLinkPathLong--) | लिंक्ड छवि का URL लौटाता है। |
| [getImageTransform()](#getImageTransform--) | छवि ट्रांसफ़ॉर्म प्रभावों का संग्रह लौटाता है। |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

एंबेडेड छवि लौटाता है। केवल-पढ़ने योग्य [IPPImage](../../com.aspose.slides/ippimage)।

**वापसी:**
[IPPImage](../../com.aspose.slides/ippimage)
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

लिंक्ड छवि का URL लौटाता है। केवल-पढ़ने योग्य String।

**वापसी:**
java.lang.String
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOCollectionEffectiveData getImageTransform()
```

छवि ट्रांसफ़ॉर्म प्रभावों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)।

**वापसी:**
[IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)