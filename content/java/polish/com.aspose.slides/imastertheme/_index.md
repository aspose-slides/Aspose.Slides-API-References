---
title: IMasterTheme
second_title: Aspose.Slides dla Dokumentacji API Javy
description: Reprezentuje motyw główny.
type: docs
url: /pl/com.aspose.slides/imastertheme/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Reprezentuje motyw główny.
## Metody

| Metoda | Opis |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Zwraca kolekcję dodatkowych schematów kolorów. |
| [getName()](#getName--) | Zwraca nazwę motywu. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca nazwę motywu. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

Zwraca kolekcję dodatkowych schematów kolorów. Te schematy nie wpływają na wygląd prezentacji, mogą być wybrane jako główny schemat kolorów dla slajdu. Tylko do odczytu [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Zwraca:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

Zwraca nazwę motywu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Zwraca nazwę motywu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |