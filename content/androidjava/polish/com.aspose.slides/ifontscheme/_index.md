---
title: IFontScheme
second_title: Aspose.Slides dla Androida przez odwołanie API Java
description: Przechowuje czcionki zdefiniowane w motywie.
type: docs
url: /pl/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Przechowuje czcionki zdefiniowane w motywie.
## Metody

| Method | Description |
| --- | --- |
| [getMinor()](#getMinor--) | Zwraca kolekcję czcionek dla części "body" slajdu. |
| [getMajor()](#getMajor--) | Zwraca kolekcję czcionek dla części "heading" slajdu. |
| [getName()](#getName--) | Zwraca nazwę schematu czcionek. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca nazwę schematu czcionek. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Zwraca kolekcję czcionek dla części "body" slajdu. Tylko do odczytu [IFonts](../../com.aspose.slides/ifonts).

**Zwraca:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Zwraca kolekcję czcionek dla części "heading" slajdu. Tylko do odczytu [IFonts](../../com.aspose.slides/ifonts).

**Zwraca:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Zwraca nazwę schematu czcionek. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Zwraca nazwę schematu czcionek. Odczyt/zapis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |