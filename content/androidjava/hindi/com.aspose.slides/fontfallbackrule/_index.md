---
title: FontFallBackRule
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: फ़ॉन्ट फॉलबैक नियम का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/fontfallbackrule/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

फ़ॉन्ट फॉलबैक नियम का प्रतिनिधित्व करता है
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | एक नया उदाहरण बनाता है। |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | एक नया उदाहरण बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट जोड़ता है। |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट जोड़ता है। |
| [getRangeStartIndex()](#getRangeStartIndex--) | सतत Unicode रेंज का पहला इंडेक्स प्राप्त करता है। |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | सतत Unicode रेंज का पहला इंडेक्स प्राप्त करता है। |
| [getRangeEndIndex()](#getRangeEndIndex--) | सतत Unicode रेंज का अंतिम इंडेक्स प्राप्त करता है। |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | सतत Unicode रेंज का अंतिम इंडेक्स प्राप्त करता है। |
| [getCount()](#getCount--) | रेंज के लिए वास्तव में परिभाषित फ़ॉन्ट्स की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर फ़ॉन्ट का नाम प्राप्त करता है। |
| [clear()](#clear--) | सूची से सभी फ़ॉन्ट्स हटाता है। |
| [remove(String fontName)](#remove-java.lang.String-) | सूची से एक विशिष्ट FallBack फ़ॉन्ट की पहली घटना हटाता है। |
| [removeAt(int index)](#removeAt-int-) | सूची के निर्दिष्ट इंडेक्स पर FallBack फ़ॉन्ट हटाता है। |
| [toArray()](#toArray--) | इस नियम के सभी FallBack फ़ॉन्ट्स के साथ एक एरे बनाता और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | सूची में निर्दिष्ट रेंज से सभी FallBack फ़ॉन्ट्स के साथ एक एरे बनाता और लौटाता है। |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | संग्रह में निर्दिष्ट नियम का इंडेक्स लौटाता है। |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


एक नया उदाहरण बनाता है।

--------------------

> ```
> // एक फ़ॉन्ट के साथ FantFallBackRule का नया उदाहरण बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // कई फ़ॉन्ट्स के साथ FantFallBackRule का नया उदाहरण बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Minché, MS Gothic, Tahoma");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | long | Unicode रेंज का प्रारंभिक इंडेक्स |
| endIndex | long | Unicode रेंज का अंतिम इंडेक्स |
| fontNames | java.lang.String | FallBack के लिए फ़ॉन्ट का नाम या नाम (कॉमा द्वारा विभाजित) |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


एक नया उदाहरण बनाता है।

--------------------

> ```
> // दो फ़ॉन्ट्स के साथ FantFallBackRule का नया उदाहरण बनाएं
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // कई फ़ॉन्ट्स के साथ FantFallBackRule का नया उदाहरण बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | long | Unicode रेंज का प्रारंभिक इंडेक्स |
| endIndex | long | Unicode रेंज का अंतिम इंडेक्स |
| fontNames | java.lang.String[] | FallBack के लिए फ़ॉन्ट का नाम या नाम (कॉमा द्वारा विभाजित) |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट जोड़ता है।

--------------------

> ```
> // FontFallBackRule का नया उदाहरण बनाएं
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // नियम में दूसरा फ़ॉन्ट जोड़ें 
>  newRule.addFallBackFonts("MS Gothic");
>  // नियम में तीसरा और चौथा फ़ॉन्ट जोड़ें 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | FallBack के लिए फ़ॉन्ट का नाम या नाम (कॉमा द्वारा विभाजित) |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट जोड़ता है।

--------------------

> ```
> // FontFallBackRule का नया उदाहरण बनाएं
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // नियम में अतिरिक्त तीन फ़ॉन्ट्स जोड़ें 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack के लिए फ़ॉन्ट का नाम या नाम (कॉमा द्वारा विभाजित) |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


सतत Unicode रेंज का पहला इंडेक्स प्राप्त करता है।

**वापसी:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


सतत Unicode रेंज का पहला इंडेक्स प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


सतत Unicode रेंज का अंतिम इंडेक्स प्राप्त करता है।

**वापसी:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


सतत Unicode रेंज का अंतिम इंडेक्स प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


रेंज के लिए वास्तव में परिभाषित फ़ॉन्ट्स की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**वापसी:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


निर्दिष्ट इंडेक्स पर फ़ॉन्ट का नाम प्राप्त करता है। केवल-पढ़ने योग्य [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


सूची से सभी फ़ॉन्ट्स हटाता है।

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


सूची से एक विशिष्ट FallBack फ़ॉन्ट की पहली घटना हटाता है।

--------------------

> ```
> // एक नियम बनाएं जिसमें फ़ॉन्ट्स की सूची हो।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // सूची से Tahoma हटाएँ।
>  newRule.remove("Tahoma");
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | हटाने के लिए फ़ॉन्ट का नाम। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


सूची के निर्दिष्ट इंडेक्स पर FallBack फ़ॉन्ट हटाता है।

--------------------

> ```
> // एक नियम बनाएं जिसमें फ़ॉन्ट्स की सूची हो।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //सूची से Tahoma हटाएँ।
>  newRule.remove(2);
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले फ़ॉन्ट का शून्य-आधारित इंडेक्स। |

### toArray() {#toArray--}
```
public final String[] toArray()
```


इस नियम के सभी FallBack फ़ॉन्ट्स के साथ एक एरे बनाता और लौटाता है।

--------------------

> ```
> // एक नियम बनाएं जिसमें फ़ॉन्ट्स की सूची हो।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // सभी फ़ॉन्ट नामों को एरे के रूप में प्राप्त करें।
>  String[] fontNames = newRule.toArray();
```

**वापसी:**
java.lang.String[] - स्ट्रिंग की एरे
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


सूची में निर्दिष्ट रेंज से सभी FallBack फ़ॉन्ट्स के साथ एक एरे बनाता और लौटाता है।

```
// एक नियम बनाएं जिसमें फ़ॉन्ट्स की सूची हो।
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // आखिरी दो फ़ॉन्ट नामों को एरे के रूप में प्राप्त करें।
 String[] fontNames = newRule.toArray(2, 2);
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | जोड़ने वाले पहले फ़ॉन्ट का इंडेक्स। |
| count | int | जोड़ने वाले फ़ॉन्ट्स की संख्या। |

**वापसी:**
java.lang.String[] - स्ट्रिंग की एरे
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


संग्रह में निर्दिष्ट नियम का इंडेक्स लौटाता है।

--------------------

> ```
> // एक नियम बनाएं जिसमें फ़ॉन्ट्स की सूची हो।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma का इंडेक्स प्राप्त करें।
>  int tahomaIndex = newRule.indexOf("Tahoma");
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | खोजने के लिए फ़ॉन्ट का नाम। |

**वापसी:**
int - फ़ॉन्ट का इंडेक्स या -1 यदि फ़ॉन्ट सूची में नहीं मिला।