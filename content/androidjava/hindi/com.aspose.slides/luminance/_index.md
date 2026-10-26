---
title: Luminance
second_title: Android के लिये Aspose.Slides, Java API रेफ़रेंस
description: एक Luminance प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/luminance/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफेस:**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

Represents a Luminance effect. Brightness linearly shifts all colors closer to white or black. Contrast scales all colors to be either closer or further apart.

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Luminance effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [Luminance](../../com.aspose.slides/luminance) is equal to the current [Luminance](../../com.aspose.slides/luminance). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```

Gets effective Luminance effect data with the inheritance applied.

**रिटर्न:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - एक [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determines whether the specified [Luminance](../../com.aspose.slides/luminance) is equal to the current [Luminance](../../com.aspose.slides/luminance).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [Luminance](../../com.aspose.slides/luminance). |

**रिटर्न:**
boolean - सही यदि वस्तुएँ समान हैं; अन्यथा, गलत.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Serves as a hash function for a particular type.

**रिटर्न:**
int - वर्तमान वस्तु के लिए एक हैश कोड.