---
title: FontFallBackRulesCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: उपयोगकर्ता द्वारा परिभाषित FontFallBack नियमों का संग्रह दर्शाता है
type: docs
url: /hi/com.aspose.slides/fontfallbackrulescollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

FontFallBack नियमों का एक संग्रह दर्शाता है, जिसे उपयोगकर्ता द्वारा निर्धारित किया गया है
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में मौजूद नियमों की संख्या प्राप्त करता है। |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | संग्रह के अंत में निर्दिष्ट FallBack नियम जोड़ता है। |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | संग्रह से विशिष्ट FallBack नियम की पहली घटना को हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर नियम प्राप्त करता है। |
| [iterator()](#iterator--) | एक enumerator लौटाता है जो संग्रह के माध्यम से इटर करता है। |
| [iteratorJava()](#iteratorJava--) | पूरा संग्रह के लिए एक java iterator लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट array में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच synchronized (थ्रेड-सेफ) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक synchronization root लौटाता है। |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```


संग्रह में वास्तव में मौजूद नियमों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```


संग्रह के अंत में एक निर्दिष्ट FallBack नियम जोड़ता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //फ़ॉन्ट्समैनेजर से खाली या पूर्व-आरंभित नियम संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //संग्रह में नया नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | जोड़ने के लिए निर्दिष्ट नियम |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```


संग्रह से विशिष्ट FallBack नियम की पहली घटना को हटाता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //फ़ॉन्ट्समैनेजर से खाली या पूर्व-आरंभित नियम संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //संग्रह में कई नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //संग्रह में पहले नियम की वस्तु प्राप्त करना
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //हटाना 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | संग्रह से हटाने के लिए नियम। |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```


निर्दिष्ट अनुक्रमांक पर नियम प्राप्त करता है। केवल-पढ़ने योग्य [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //फ़ॉन्ट्समैनेजर से खाली या पूर्व-आरंभित नियम संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //संग्रह में कई नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //संग्रह में पहले नियम की वस्तु पुनः प्राप्त करना
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```


एक enumerator लौटाता है जो संग्रह के माध्यम से इटर करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```


पूरा संग्रह के लिए एक java iterator लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


संग्रह से सभी तत्व निर्दिष्ट array में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य array। |
| index | int | लक्ष्य array में प्रारंभिक अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच synchronized (थ्रेड-सेफ) है या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक synchronization root लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object