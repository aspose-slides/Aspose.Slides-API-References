---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides Android számára Java API referenciája
description: A felhasználó által definiált FontFallBack szabályok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ifontfallbackrulescollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

A felhasználó által definiált FontFallBack szabályok gyűjteménye.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű szabályt adja vissza. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Új FallBack szabályt ad a gyűjtemény végéhez. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Eltávolítja egy adott FallBack szabály első előfordulását a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```


A megadott indexű szabályt adja vissza. Csak olvasható [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Üres vagy előre inicializált szabálykészlet lekérése a FontsManager-től
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Több szabály hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Az első szabály objektumának lekérése a gyűjteményből
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```


Új FallBack szabályt ad a gyűjtemény végéhez.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Üres vagy előre inicializált szabálykészlet lekérése a FontsManager-ből
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Új szabály hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | A hozzáadandó szabály |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```


Eltávolítja egy adott FallBack szabály első előfordulását a gyűjteményből.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Üres vagy előre inicializált szabálykészlet lekérése a FontsManager-ből
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Több szabály hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Az első szabály objektumának lekérése a gyűjteményből
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Eltávolítás
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | A gyűjteményből eltávolítandó szabály. |