---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: उपयोगकर्ता द्वारा परिभाषित FontFallBack नियमों का एक संग्रह दर्शाता है
type: docs
url: /hi/com.aspose.slides/ifontfallbackrulescollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

उपयोगकर्ता द्वारा परिभाषित FontFallBack नियमों का एक संग्रह दर्शाता है
## विधियाँ

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर नियम प्राप्त करता है। |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | संग्रह के अंत में एक नया FallBack नियम जोड़ें। |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | संग्रह से एक विशिष्ट FallBack नियम की पहली आवृत्ति हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```

निर्दिष्ट सूचकांक पर नियम प्राप्त करता है। केवल-पढ़ने-योग्य [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager से खाली या पूर्व-प्राथमिकीकृत नियमों का संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //संग्रह में कई नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //संग्रह में पहले नियम की वस्तु को प्राप्त करना
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

**वापसी:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```

संग्रह के अंत में एक नया FallBack नियम जोड़ें।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager से खाली या पूर्व-प्राथमिकीकृत नियमों का संग्रह प्राप्त करना
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
public abstract void remove(IFontFallBackRule targetRule)
```

संग्रह से एक विशिष्ट FallBack नियम की पहली आवृत्ति हटाता है।

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager से खाली या पूर्व-प्रारंभित नियमों का संग्रह प्राप्त करना
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //संग्रह में कई नियम जोड़ना
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //संग्रह में पहले नियम की वस्तु को प्राप्त करना
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