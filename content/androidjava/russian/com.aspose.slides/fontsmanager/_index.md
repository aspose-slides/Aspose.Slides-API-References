---
title: FontsManager
second_title: Aspose.Slides для Android через справочник Java API
description: Управляет шрифтами в презентации.
type: docs
url: /ru/com.aspose.slides/fontsmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Управляет шрифтами в презентации.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Загрузить презентацию
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Загрузить исходный шрифт, который будет заменён
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Сохранить презентацию
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Методы

| Метод | Описание |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Подстановки шрифтов, используемые при отрисовке. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Подстановки шрифтов, используемые при отрисовке. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Представляет пользовательскую коллекцию правил FontFallBack для управления коллекциями шрифтов с целью корректных подстановок через механизм fallback. Чтение/запись [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Представляет пользовательскую коллекцию правил FontFallBack для управления коллекциями шрифтов с целью корректных подстановок через механизм fallback. Чтение/запись [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Возвращает шрифты, используемые в презентации |
| [getSubstitutions()](#getSubstitutions--) | Получает информацию о шрифтах, которые будут заменены при отрисовке презентации. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Получает информацию о шрифтах, которые будут заменены при отрисовке указанных слайдов. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Возвращает встроенные в презентацию шрифты |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Удаляет встроенный шрифт |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Добавляет встроенный шрифт |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Добавляет встроенный шрифт |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Заменить шрифт в презентации |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Заменить шрифт в презентации, используя информацию, предоставленную в [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Заменить шрифт в презентации, используя информацию, предоставленную в коллекции [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Получает массив байтов, представляющий данные шрифта для указанного стиля и данных шрифта. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Определяет уровень встраивания шрифта на основе предоставленного массива байтов и имени шрифта. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Подстановки шрифтов, используемые при отрисовке. Чтение/запись [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Возвращаемое значение:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Подстановки шрифтов, используемые при отрисовке. Чтение/запись [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Представляет пользовательскую коллекцию правил FontFallBack для управления коллекциями шрифтов с целью корректных подстановок через механизм fallback. Чтение/запись [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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


**Возвращаемое значение:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Представляет пользовательскую коллекцию правил FontFallBack для управления коллекциями шрифтов с целью корректных подстановок через механизм fallback. Чтение/запись [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
public final IFontData[] getFonts()
```

Возвращает шрифты, используемые в презентации

**Возвращаемое значение:**
com.aspose.slides.IFontData[] - Массив шрифтов

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Получает информацию о шрифтах, которые будут заменены при отрисовке презентации.

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


**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Коллекция всех подстановок шрифтов [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Получает информацию о шрифтах, которые будут заменены при отрисовке указанных слайдов.

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
| slides | int[] | Массив индексов слайдов, для которых нужно получить информацию о подстановках шрифтов, начиная с 1. |

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Коллекция всех подстановок шрифтов ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) для указанных слайдов.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Возвращает встроенные в презентацию шрифты

**Возвращаемое значение:**
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Удаляет встроенный шрифт

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Добавляет встроенный шрифт

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Добавляет встроенный шрифт

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Заменить шрифт в презентации

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Исходный шрифт |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Целевой шрифт |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Заменить шрифт в презентации, используя информацию, предоставленную в [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Информация о подстановке шрифта |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Заменить шрифт в презентации, используя информацию, предоставленную в коллекции [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Коллекция правил подстановки шрифтов |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Получает массив байтов, представляющий данные шрифта для указанного стиля и данных шрифта.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Получить все шрифты, используемые в презентации
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
| fontStyle | int | Стиль шрифта, для которого требуется получить данные [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Возвращаемое значение:**
byte[] - Массив байтов, содержащий данные шрифта для указанного стиля. Если данные шрифта или стиль не найдены, возвращает null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Определяет уровень встраивания шрифта на основе предоставленного массива байтов и имени шрифта.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Получить все шрифты, используемые в презентации
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Получить массив байтов, представляющий обычный стиль первого шрифта в презентации
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Определить уровень встраивания шрифта
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontBytes | byte[] | Массив байтов, содержащий данные шрифта. |
| fontName | java.lang.String | Имя шрифта. |

**Возвращаемое значение:**
int - Уровень встраивания указанного шрифта.