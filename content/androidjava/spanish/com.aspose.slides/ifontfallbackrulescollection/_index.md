---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa una colección de reglas FontFallBack definidas por el usuario
type: docs
url: /es/com.aspose.slides/ifontfallbackrulescollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

Representa una colección de reglas FontFallBack, definidas por el usuario
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene la regla en el índice especificado. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Agrega una nueva regla FallBack al final de la colección. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Elimina la primera ocurrencia de una regla FallBack específica de la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```


Obtiene la regla en el índice especificado. Solo lectura [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Obtención de una colección de reglas vacía o preinicializada del FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Agregando varias reglas a la colección
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Recuperación del objeto de la primera regla en la colección
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```


Agrega una nueva regla FallBack al final de la colección.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Obtención de una colección vacía o preinicializada de reglas del FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Agregando una nueva regla a la colección
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Regla especificada para agregar |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```


Elimina la primera ocurrencia de una regla FallBack específica de la colección.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Obtención de una colección vacía o preinicializada de reglas del FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Agregando varias reglas a la colección
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Recuperación del objeto de la primera regla en la colección
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Eliminando 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | La regla a eliminar de la colección. |