---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Reprezentuje kolekcję reguł FontFallBack zdefiniowanych przez użytkownika
type: docs
url: /pl/com.aspose.slides/ifontfallbackrulescollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

Reprezentuje kolekcję reguł FontFallBack zdefiniowanych przez użytkownika
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera regułę pod określonym indeksem. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Dodaje nową regułę FallBack na koniec kolekcji. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Usuwa pierwsze wystąpienie określonej reguły FallBack z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```


Pobiera regułę pod określonym indeksem. Tylko do odczytu [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Pobieranie pustej lub wstępnie zainicjowanej kolekcji reguł z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Dodawanie kilku reguł do kolekcji
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Pobieranie obiektu pierwszej reguły w kolekcji
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```


Dodaje nową regułę FallBack na koniec kolekcji.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Pobieranie pustej lub wstępnie zainicjowanej kolekcji reguł z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Dodawanie nowej reguły do kolekcji
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Określona reguła do dodania |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```


Usuwa pierwsze wystąpienie określonej reguły FallBack z kolekcji.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Pobieranie pustej lub wstępnie zainicjowanej kolekcji reguł z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Dodawanie kilku reguł do kolekcji
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Pobieranie obiektu pierwszej reguły w kolekcji
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Usuwanie 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Reguła do usunięcia z kolekcji. |