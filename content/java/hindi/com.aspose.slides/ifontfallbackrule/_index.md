---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: फ़ॉन्ट फ़ॉलबैक नियम का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

फ़ॉन्ट फ़ॉलबैक नियम का प्रतिनिधित्व करता है
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट(स) जोड़ता है। |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट जोड़ता है। |
| [getRangeStartIndex()](#getRangeStartIndex--) | सतत यूनिकोड रेंज का पहला सूचकांक प्राप्त करता है। |
| [getRangeEndIndex()](#getRangeEndIndex--) | सतत यूनिकोड रेंज का अंतिम सूचकांक प्राप्त करता है। |
| [getCount()](#getCount--) | रेंज के लिए वास्तव में परिभाषित फ़ॉन्ट्स की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर फ़ॉन्ट नाम प्राप्त करता है। |
| [clear()](#clear--) | सूची से सभी फ़ॉन्ट्स हटाता है। |
| [remove(String fontName)](#remove-java.lang.String-) | सूची से विशिष्ट FallBack फ़ॉन्ट की पहली उपस्थिति हटाता है। |
| [removeAt(int index)](#removeAt-int-) | सूची के निर्दिष्ट सूचकांक पर FallBack फ़ॉन्ट हटाता है। |
| [toArray()](#toArray--) | इस नियम के सभी FallBack फ़ॉन्ट्स के साथ एक एरे बनाता और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | सूची में निर्दिष्ट रेंज से सभी FallBack फ़ॉन्ट्स के साथ एक एरे बनाता और लौटाता है। |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | संग्रह में निर्दिष्ट नियम का सूचकांक लौटाता है। |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```


FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट(स) जोड़ता है।

--------------------

> ```
> //फ़ॉन्ट फ़ॉलबैक नियम की नई इंस्टेंस बनाते हैं
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //नियम के लिए दूसरा फ़ॉन्ट जोड़ें 
>  newRule.addFallBackFonts("MS Gothic");
>  //नियम के लिए तीसरा और चौथा फ़ॉन्ट जोड़ें 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | FallBack के लिए फ़ॉन्ट का नाम या नाम (कॉमा द्वारा विभाजित) |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```


FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट जोड़ता है।

--------------------

> ```
> //फ़ॉन्टFallBackRule की नई इंस्टेंस बनाएं
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //नियम में अतिरिक्त तीन फ़ॉन्ट्स जोड़ें 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack के लिए फ़ॉन्ट का नाम या नाम (कॉमा द्वारा विभाजित) |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```


सतत यूनिकोड रेंज का पहला सूचकांक प्राप्त करता है।

**रिटर्न्स:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```


सतत यूनिकोड रेंज का अंतिम सूचकांक प्राप्त करता है।

**रिटर्न्स:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```


रेंज के लिए वास्तव में परिभाषित फ़ॉन्ट्स की संख्या प्राप्त करता है।

**रिटर्न्स:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```


निर्दिष्ट सूचकांक पर फ़ॉन्ट नाम प्राप्त करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न्स:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```


सूची से सभी फ़ॉन्ट्स हटाता है।

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```


सूची से विशिष्ट FallBack फ़ॉन्ट की पहली उपस्थिति हटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // सूची से Tahoma हटाना
>  newRule.remove("Tahoma");
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | हटाने हेतु फ़ॉन्ट का नाम। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


सूची के निर्दिष्ट सूचकांक पर FallBack फ़ॉन्ट हटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // सूची से Tahoma हटाना
>  newRule.remove(2);
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने हेतु फ़ॉन्ट का शून्य-आधारित सूचकांक। |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```


इस नियम के सभी FallBack फ़ॉन्ट्स के साथ एक एरे बनाता और लौटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // सभी फ़ॉन्ट-नामों को एरे के रूप में प्राप्त करें
>  String[] fontNames = newRule.toArray();
> ```


**रिटर्न्स:**
java.lang.String[] - स्ट्रिंग की एरे
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```


सूची में निर्दिष्ट रेंज से सभी FallBack फ़ॉन्ट्स के साथ एक एरे बनाता और लौटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // अंतिम दो फ़ॉन्ट-नामों को एरे के रूप में प्राप्त करें
>  String[] fontNames = newRule.toArray(2,2);
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | जोड़ने के लिए पहले फ़ॉन्ट का सूचकांक। |
| count | int | जोड़ने के लिए फ़ॉन्ट्स की संख्या। |

**रिटर्न्स:**
java.lang.String[] - स्ट्रिंग की एरे
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```


संग्रह में निर्दिष्ट नियम का सूचकांक लौटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma का सूचकांक प्राप्त करें
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | खोजने के लिए फ़ॉन्ट का नाम। |

**रिटर्न्स:**
int - फ़ॉन्ट का सूचकांक या -1 यदि फ़ॉन्ट सूची में नहीं मिला।