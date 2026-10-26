---
title: IBehaviorProperty
second_title: Aspose.Slides for Android via Java API Reference
description: Represent property types for animation behavior.
type: docs
url: /es/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

Representa tipos de propiedad para el comportamiento de animación. Sigue la lista de propiedades de https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx y https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Métodos

| Método | Descripción |
| --- | --- |
| [getValue()](#getValue--) | Valor de la propiedad |
| [isCustom()](#isCustom--) | Muestra si esta propiedad no pertenece a la lista de propiedades predefinidas en la especificación: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
### getValue() {#getValue--}
```
public abstract String getValue()
```


Valor de la propiedad

**Devuelve:**
java.lang.String
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Muestra si esta propiedad no pertenece a la lista de propiedades predefinidas en la especificación: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Devuelve:**
boolean