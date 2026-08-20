---
title: FontFallBackRule
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: फ़ॉन्ट फ़ॉल्बैक नियम का प्रतिनिधित्व करता है
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

फ़ॉन्ट फॉल्बैक नियम का प्रतिनिधित्व करता है
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | एक नया आदर्श बनाता है। |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | एक नया आदर्श बनाता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट (फ़ॉन्ट्स) जोड़ता है। |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट्स जोड़ता है। |
| [getRangeStartIndex()](#getRangeStartIndex--) | लगातार यूनिकोड रेंज का पहला सूचकांक प्राप्त करता है। |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | लगातार यूनिकोड रेंज का पहला सूचकांक प्राप्त करता है। |
| [getRangeEndIndex()](#getRangeEndIndex--) | लगातार यूनिकोड रेंज का अंतिम सूचकांक प्राप्त करता है। |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | लगातार यूनिकोड रेंज का अंतिम सूचकांक प्राप्त करता है। |
| [getCount()](#getCount--) | रेंज के लिए वास्तव में परिभाषित फ़ॉन्ट्स की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर फ़ॉन्ट का नाम प्राप्त करता है। |
| [clear()](#clear--) | सभी फ़ॉन्ट्स को सूची से हटाता है। |
| [remove(String fontName)](#remove-java.lang.String-) | सूची से विशिष्ट FallBack फ़ॉन्ट की पहली प्रकटि हटाता है। |
| [removeAt(int index)](#removeAt-int-) | सूची के निर्दिष्ट सूचकांक पर FallBack फ़ॉन्ट हटाता है। |
| [toArray()](#toArray--) | इस नियम के सभी FallBack फ़ॉन्ट्स के साथ एक ऐरे बनाता है और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | सूची में निर्दिष्ट रेंज से सभी FallBack फ़ॉन्ट्स के साथ एक ऐरे बनाता है और लौटाता है। |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | संग्रह में निर्दिष्ट नियम का सूचकांक लौटाता है। |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


एक नया आदर्श बनाता है।

--------------------

> ```
> // एक फ़ॉन्ट के साथ FantFallBackRule का नया उदाहरण बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // कई फ़ॉन्ट्स के साथ FantFallBackRule का नया उदाहरण बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | long | यूनिकोड रेंज का प्रारंभिक सूचकांक |
| endIndex | long | यूनिकोड रेंज का अंतिम सूचकांक |
| fontNames | java.lang.String | FallBack के लिए फ़ॉन्ट का नाम या नाम (कॉमा द्वारा अलग किया गया) |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


एक नया आदर्श बनाता है।

--------------------

> ```
> // दो फ़ॉन्ट्स के साथ FantFallBackRule का नया उदाहरण बनाएं
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // कई फ़ॉन्ट्स के साथ FantFallBackRule का नया उदाहरण बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | long | यूनिकोड रेंज का प्रारंभिक सूचकांक |
| endIndex | long | यूनिकोड रेंज का अंतिम सूचकांक |
| fontNames | java.lang.String[] | FallBack के लिए फ़ॉन्ट का नाम या नाम (कॉमा द्वारा अलग किया गया) |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट (फ़ॉन्ट्स) जोड़ता है।

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
| fontName | java.lang.String | FallBack के लिए फ़ॉन्ट का नाम या नाम (कॉमा द्वारा अलग किया गया) |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट्स जोड़ता है।

--------------------

> ```
> // FontFallBackRule का नया उदाहरण बनाएं
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // नियम में तीन और फ़ॉन्ट जोड़ें 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack के लिए फ़ॉन्ट का नाम या नाम (कॉमा द्वारा अलग किया गया) |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


लगातार यूनिकोड रेंज का पहला सूचकांक प्राप्त करता है।

**वापसी मान:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


लगातार यूनिकोड रेंज का पहला सूचकांक प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


लगातार यूनिकोड रेंज का अंतिम सूचकांक प्राप्त करता है।

**वापसी मान:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


लगातार यूनिकोड रेंज का अंतिम सूचकांक प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


रेंज के लिए वास्तव में परिभाषित फ़ॉन्ट्स की संख्या प्राप्त करता है। Read-only int.

**वापसी मान:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


निर्दिष्ट सूचकांक पर फ़ॉन्ट का नाम प्राप्त करता है। Read-only [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी मान:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


सभी फ़ॉन्ट्स को सूची से हटाता है।

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


सूची से विशिष्ट FallBack फ़ॉन्ट की पहली प्रकटि हटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // सूची से Tahoma को हटाएँ।
>  newRule.remove("Tahoma");
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | सूची से हटाने के लिए फ़ॉन्ट का नाम। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


सूची के निर्दिष्ट सूचकांक पर FallBack फ़ॉन्ट हटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // सूची से Tahoma को हटाएँ।
>  newRule.remove(2);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए फ़ॉन्ट का शून्य-आधारित सूचकांक। |

### toArray() {#toArray--}
```
public final String[] toArray()
```


इस नियम के सभी FallBack फ़ॉन्ट्स के साथ एक ऐरे बनाता है और लौटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // सभी फ़ॉन्ट नामों को ऐरे के रूप में प्राप्त करें।
>  String[] fontNames = newRule.toArray();
> ```

**वापसी मान:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


निर्दिष्ट रेंज से सूची में सभी FallBack फ़ॉन्ट्स के साथ एक ऐरे बनाता है और लौटाता है।

```
// फ़ॉन्ट्स की सूची वाला नियम बनाएं।
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // आखिरी दो फ़ॉन्ट नामों को ऐरे के रूप में प्राप्त करें।
 String[] fontNames = newRule.toArray(2, 2);
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | जोड़ने के लिए पहला फ़ॉन्ट का सूचकांक। |
| count | int | जोड़ने के लिए फ़ॉन्ट्स की संख्या। |

**वापसी मान:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


संग्रह में निर्दिष्ट नियम का सूचकांक लौटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma का सूचकांक प्राप्त करें।
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | खोजने के लिए फ़ॉन्ट का नाम। |

**वापसी मान:**
int - Index of a font or -1 if font not found in list.