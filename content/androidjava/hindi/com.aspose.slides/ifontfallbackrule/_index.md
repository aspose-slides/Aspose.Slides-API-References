---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Represents font fallback rule
type: docs
url: /hi/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

फ़ॉन्ट फ़ॉलबैक नियम को दर्शाता है
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट (फ़ॉन्ट्स) जोड़ता है। |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट जोड़ता है। |
| [getRangeStartIndex()](#getRangeStartIndex--) | सतत Unicode रेंज का पहला सूचकांक प्राप्त करता है। |
| [getRangeEndIndex()](#getRangeEndIndex--) | सतत Unicode रेंज का अंतिम सूचकांक प्राप्त करता है। |
| [getCount()](#getCount--) | रेंज के लिए वास्तविक में परिभाषित फ़ॉन्ट्स की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर फ़ॉन्ट का नाम प्राप्त करता है। |
| [clear()](#clear--) | सूची से सभी फ़ॉन्ट्स हटाता है। |
| [remove(String fontName)](#remove-java.lang.String-) | सूची से एक विशेष FallBack फ़ॉन्ट की पहली उपस्थिति हटाता है। |
| [removeAt(int index)](#removeAt-int-) | सूची में निर्दिष्ट सूचकांक पर FallBack फ़ॉन्ट हटाता है। |
| [toArray()](#toArray--) | इस नियम के सभी FallBack फ़ॉन्ट्स के साथ एक ऐरे बनाता है और लौटाता है। |
| [toArray(int startIndex, int count)](#toArray-int-int-) | सूची में निर्दिष्ट रेंज से सभी FallBack फ़ॉन्ट्स के साथ एक ऐरे बनाता है और लौटाता है। |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | संग्रह में निर्दिष्ट नियम का सूचकांक लौटाता है। |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```


FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट (फ़ॉन्ट्स) जोड़ता है।

--------------------

> ```
> //नए उदाहरण का निर्माण FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //नियम में दूसरा फ़ॉन्ट जोड़ें 
>  newRule.addFallBackFonts("MS Gothic");
>  //नियम में तीसरा और चौथा फ़ॉन्ट्स जोड़ें 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | FallBack के लिए फ़ॉन्ट का नाम या नाम (कोमा द्वारा अलग किए गए) |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```


FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट जोड़ता है।

--------------------

> ```
> //नए FontFallBackRule का उदाहरण बनाएं
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //नियम में अतिरिक्त तीन फ़ॉन्ट्स जोड़ें 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack के लिए फ़ॉन्ट के नाम या नाम (कोमा द्वारा अलग किए गए) |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```


सतत Unicode रेंज का पहला सूचकांक प्राप्त करता है।

**रिटर्न:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```


सतत Unicode रेंज का अंतिम सूचकांक प्राप्त करता है।

**रिटर्न:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```


रेंज के लिए वास्तविक में परिभाषित फ़ॉन्ट्स की संख्या प्राप्त करता है।

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```


निर्दिष्ट सूचकांक पर फ़ॉन्ट का नाम प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
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


सूची से एक विशेष FallBack फ़ॉन्ट की पहली उपस्थिति हटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //सूची से Tahoma को हटाया गया।
>  newRule.remove("Tahoma");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | हटाने के लिए फ़ॉन्ट का नाम। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


सूची में निर्दिष्ट सूचकांक पर FallBack फ़ॉन्ट हटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // सूची से Tahoma को हटाया गया
>  newRule.remove(2);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले फ़ॉन्ट का शून्य-आधारित सूचकांक। |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```


इस नियम के सभी FallBack फ़ॉन्ट्स के साथ एक ऐरे बनाता है और लौटाता है।

--------------------

> ```
> // एक नियम बनाएं जिसमें फ़ॉन्ट्स की सूची हो।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // सभी फ़ॉन्ट-नामों को ऐरे के रूप में प्राप्त करें
>  String[] fontNames = newRule.toArray();
> ```

**रिटर्न:**
java.lang.String[] - स्ट्रिंग का ऐरे
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```


सूची में निर्दिष्ट रेंज से सभी FallBack फ़ॉन्ट्स के साथ एक ऐरे बनाता है और लौटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //आख़िरी दो फ़ॉन्ट-नामों को ऐरे के रूप में प्राप्त करें
>  String[] fontNames = newRule.toArray(2,2);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | पहला फ़ॉन्ट जोड़ने का सूचकांक। |
| count | int | जोड़ने वाले फ़ॉन्ट्स की संख्या। |

**रिटर्न:**
java.lang.String[] - स्ट्रिंग का ऐरे
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```


संग्रह में निर्दिष्ट नियम का सूचकांक लौटाता है।

--------------------

> ```
> // फ़ॉन्ट्स की सूची वाला नियम बनाएं।
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Tahoma का सूचकांक प्राप्त करें
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | खोजने के लिए फ़ॉन्ट का नाम। |

**रिटर्न:**
int - फ़ॉन्ट का सूचकांक या -1 यदि फ़ॉन्ट सूची में नहीं मिला।