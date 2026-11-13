---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Manages fonts across the presentation.
type: docs
url: /ru/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Управляет шрифтами презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Замены шрифтов, используемые при рендеринге Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Замены шрифтов, используемые при рендеринге Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов с целью правильных замен с помощью функции fallback Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов с целью правильных замен с помощью функции fallback Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Возвращает шрифты, используемые в презентации |
| [getSubstitutions()](#getSubstitutions--) | Получает информацию о шрифтах, которые будут заменены при рендеринге презентации. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Получает информацию о шрифтах, которые будут заменены при рендеринге указанных слайдов. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Возвращает встроенные в презентацию шрифты |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Удаляет встроенный шрифт |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Добавляет встроенный шрифт. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Добавляет встроенный шрифт |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Заменить шрифт в презентации |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Заменить шрифт в презентации, используя информацию, предоставленную в [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Заменить шрифт в презентации, используя информацию, предоставленную в коллекции [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Получает массив байт, представляющий данные шрифта для указанного стиля шрифта и данных шрифта. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Определяет уровень внедрения шрифта по заданному массиву байт и имени шрифта. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Указывает, следует ли отдавать предпочтение зарегистрированным шрифтам перед встроенными шрифтами с тем же именем и стилем. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Указывает, следует ли отдавать предпочтение зарегистрированным шрифтам перед встроенными шрифтами с тем же именем и стилем. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Замены шрифтов, используемые при рендеринге Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Возвращает:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Замены шрифтов, используемые при рендеринге Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов с целью правильных замен с помощью функции fallback Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Получение пустой или предварительно инициализированной коллекции правил из FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // добавление правил в коллекцию
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // или 
>      // инициализация нового экземпляра коллекции правил
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // добавление правил в коллекцию
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // и замена существующей коллекции новой в FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов с целью правильных замен с помощью функции fallback Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Получение пустой или предварительно инициализированной коллекции правил из FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // добавление правил в коллекцию
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // или 
>      // инициализация нового экземпляра коллекции правил
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // добавление правил в коллекцию
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // и замена существующей коллекции новой в FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

Возвращает шрифты, используемые в презентации

**Возвращает:**
com.aspose.slides.IFontData[] - массив шрифтов

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Получает информацию о шрифтах, которые будут заменены при рендеринге презентации.

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


**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Коллекция всех замен шрифтов [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Получает информацию о шрифтах, которые будут заменены при рендеринге указанных слайдов.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      int[] targetSlides = { 1, 2, 5 };
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions(targetSlides))
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slides | int[] | Массив индексов слайдов, для которых необходимо получить информацию о замене шрифтов, начиная с 1. |

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Коллекция всех замен шрифтов ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) для указанных слайдов.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Возвращает встроенные в презентацию шрифты

**Возвращает:**
com.aspose.slides.IFontData[] - встроенные шрифты IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Удаляет встроенный шрифт

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Объект данных шрифта [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Добавляет встроенный шрифт.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Объект данных шрифта [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Правило встроенного шрифта [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Учтите, что при копировании любых шрифтов большинство из них защищены авторским правом. Сначала найдите лицензию шрифта и убедитесь, что его можно свободно перенести на другую машину.

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Добавляет встроенный шрифт

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontData | byte[] | Данные шрифта byte[] |
| embedFontRule | int | Правило встроенного шрифта [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Учтите, что при добавлении любых шрифтов большинство из них защищены авторским правом. Сначала найдите лицензию шрифта и убедитесь, что его можно свободно перенести на другую машину.

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Заменить шрифт в презентации

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Исходный шрифт |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Целевой шрифт |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Заменить шрифт в презентации, используя информацию, предоставленную в [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Информация о замене шрифта |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Заменить шрифт в презентации, используя информацию, предоставленную в коллекции [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Коллекция информации о замене шрифтов |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Получает массив байт, представляющий данные шрифта для указанного стиля шрифта и данных шрифта.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Получить все шрифты, использованные в презентации
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Получить массив байтов, представляющий обычный стиль первого шрифта в презентации
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Объект данных шрифта, содержащий информацию о шрифте [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Стиль шрифта, для которого необходимо получить данные [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Возвращает:**
byte[] - массив байт, содержащий данные шрифта для указанного стиля. Если данные шрифта или стиль не найдены, возвращается null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Определяет уровень внедрения шрифта по заданному массиву байт и имени шрифта.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Получить все шрифты, использованные в презентации
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Получить массив байтов, представляющий обычный стиль первого шрифта в презентации
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Определить уровень внедрения шрифта
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontBytes | byte[] | Массив байт, содержащий данные шрифта. |
| fontName | java.lang.String | Имя шрифта. |

**Возвращает:**
int - уровень внедрения указанного шрифта.

### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

Указывает, следует ли отдавать предпочтение зарегистрированным шрифтам перед встроенными шрифтами с тем же именем и стилем. При включении соответствующие встроенные шрифты временно заменяются соответствующими зарегистрированными шрифтами во время экспорта.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

По умолчанию **false**.

**Возвращает:**
boolean

### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

Указывает, следует ли отдавать предпочтение зарегистрированным шрифтам перед встроенными шрифтами с тем же именем и стилем. При включении соответствующие встроенные шрифты временно заменяются соответствующими зарегистрированными шрифтами во время экспорта.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

По умолчанию **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |