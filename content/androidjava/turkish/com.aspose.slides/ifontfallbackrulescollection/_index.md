---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides for Android Java API Referansı
description: Kullanıcı tarafından tanımlanan FontFallBack kurallarının bir koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/ifontfallbackrulescollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

Kullanıcı tarafından tanımlanan FontFallBack kurallarının bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki kuralı alır. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Koleksiyonun sonuna yeni bir FallBack kuralı ekler. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Koleksiyondan belirli bir FallBack kuralının ilk görünümünü kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```

Belirtilen dizindeki kuralı alır. Yalnızca okuma [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alıyor
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Koleksiyona birkaç kural ekleniyor
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Koleksiyondaki ilk kuralın nesnesi alınıyor
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```

Koleksiyonun sonuna yeni bir FallBack kuralı ekler.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alıyor
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Koleksiyona yeni bir kural ekleniyor
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Ekleme için belirtilen kural |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```

Koleksiyondan belirli bir FallBack kuralının ilk görünümünü kaldırır.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alıyor
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Koleksiyona birkaç kural ekleniyor
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Koleksiyondaki ilk kuralın nesnesi alınıyor
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Kaldırılıyor 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Koleksiyondan kaldırılacak kural. |