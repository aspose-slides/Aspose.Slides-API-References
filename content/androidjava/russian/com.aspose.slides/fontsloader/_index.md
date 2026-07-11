---
title: FontsLoader
second_title: Aspose.Slides для Android через справочник Java API
description: Класс для загрузки пользовательских шрифтов, определённых пользователем.
type: docs
url: /ru/com.aspose.slides/fontsloader/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Класс для загрузки пользовательских шрифтов, определённых пользователем. Должен использоваться перед созданием каких-либо объектов презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Добавляет дополнительные папки для поиска шрифтов. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Добавляет шрифт из двоичных данных |
| [getFontFolders()](#getFontFolders--) | Получает папки шрифтов. |
| [clearCache()](#clearCache--) | Освобождает все пользовательские шрифты, определённые пользователем |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


Добавляет дополнительные папки для поиска шрифтов.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // папки для поиска шрифтов
>  String[] folders = new String[] { dataDir };
>  // Загрузка пользовательских шрифтов из каталога
>  FontsLoader.loadExternalFonts(folders);
>  // Выполнить некоторую работу и отрисовку презентации/слайдов
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Очистить кеш шрифтов
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| directories | java.lang.String[] | Папки для чтения дополнительных шрифтов. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


Добавляет шрифт из двоичных данных

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] | Данные шрифта |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


Получает папки шрифтов. Возвращает папки, которые были добавлены с помощью метода LoadExternalFonts, а также системные папки шрифтов

**Возвращаемое значение:**
java.lang.String[] - массив, содержащий имена папок
### clearCache() {#clearCache--}
```
public static void clearCache()
```


Освобождает все пользовательские шрифты, определённые пользователем

--------------------

Этот метод должен очистить кэш пользовательских шрифтов, определённых пользователем.