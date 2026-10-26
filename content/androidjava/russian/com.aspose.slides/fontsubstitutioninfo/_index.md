---
title: FontSubstitutionInfo
second_title: Aspose.Slides для Android через справочник API Java
description: Эта структура представляет информацию о замене шрифта при его визуализации.
type: docs
url: /ru/com.aspose.slides/fontsubstitutioninfo/
---
**Наследование:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Эта структура представляет информацию о замене шрифта при его визуализации.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Создаёт экземпляр класса [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Методы

| Метод | Описание |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Указывает имя исходного шрифта в презентации. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Указывает имя заменяющего шрифта для оригинального шрифта. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

Создаёт экземпляр класса [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| originFontName | java.lang.String | Имя исходного шрифта в презентации String |
| substFontName | java.lang.String | Имя заменяющего шрифта для оригинального шрифта String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

Указывает имя исходного шрифта в презентации. Только для чтения String

**Возвращаемое значение:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

Указывает имя заменяющего шрифта для оригинального шрифта. Только для чтения String

**Возвращаемое значение:**
java.lang.String