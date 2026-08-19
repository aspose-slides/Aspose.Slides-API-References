---
title: IMasterTheme
second_title: Aspose.Slides pro Java – referenční příručka API
description: Představuje hlavní motiv.
type: docs
url: /cs/com.aspose.slides/imastertheme/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Představuje hlavní motiv.
## Metody

| Metoda | Popis |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Vrací kolekci dodatečných schémat barev. |
| [getName()](#getName--) | Vrací název motivu. |
| [setName(String value)](#setName-java.lang.String-) | Vrací název motivu. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


Vrací kolekci dodatečných schémat barev. Tato schémata nemají vliv na vzhled prezentace, mohou být vybrána jako hlavní schéma barev pro snímek. Pouze pro čtení [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Vrací:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


Vrací název motivu. Čtení/zápis String.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Vrací název motivu. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |