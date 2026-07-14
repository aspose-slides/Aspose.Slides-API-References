---
title: FontFallBackRulesCollection
second_title: Aspose.Slides for Android द्वारा Java API रेफ़रेंस
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

उपयोगकर्ता द्वारा परिभाषित FontFallBack नियमों का संग्रह दर्शाता है
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में मौजूद नियमों की संख्या प्राप्त करता है। |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | निर्दिष्ट FallBack नियम को संग्रह के अंत में जोड़ता है। |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | संग्रह से एक विशिष्ट FallBack नियम की पहली उपस्थिती को हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर नियम प्राप्त करता है। |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह में इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java इटरटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिक रूट लौटाता है। |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```


संग्रह में वास्तव में मौजूद नियमों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int।

**रिटर्न मान:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```


निर्दिष्ट FallBack नियम को संग्रह के अंत में जोड़ता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager से खाली या पूर्व-इनिशियलाइज़्ड नियम संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //नए नियम को संग्रह में जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | जोड़ने के लिए निर्दिष्ट नियम |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```


संग्रह से एक विशिष्ट FallBack नियम की पहली उपस्थिती को हटाता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager से खाली या पहले से इनिशियलाइज़्ड नियम संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //कई नियमों को संग्रह में जोड़ना
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
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | संग्रह से हटाने के लिए नियम |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```


निर्दिष्ट अनुक्रमणिका पर नियम प्राप्त करता है। केवल पढ़ने योग्य [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager से खाली या पूर्व-इनिशियलाइज़्ड नियम संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //संग्रह में कई नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //संग्रह में पहले नियम की वस्तु प्राप्त करना
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| index | int |  |

**रिटर्न मान:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```


एक एनेमरेटर लौटाता है जो संग्रह में इटररेट करता है।

**रिटर्न मान:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - एक IGenericEnumerator जो संग्रह के माध्यम से इटररेट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```


पूरे संग्रह के लिए एक java इटरटर लौटाता है।

**रिटर्न मान:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - एक java.util.Iterator जो पूरे संग्रह के लिए उपयोग किया जा सकता है।
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


संग्रह के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक अनुक्रमणिका। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सेफ़) है या नहीं। केवल पढ़ने योग्य boolean।

**रिटर्न मान:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक समकालिक रूट लौटाता है। केवल पढ़ने योग्य Object।

**रिटर्न मान:**
java.lang.Object