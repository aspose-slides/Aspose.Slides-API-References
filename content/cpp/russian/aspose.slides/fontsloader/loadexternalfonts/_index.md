---
title: LoadExternalFonts()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет дополнительные папки для поиска шрифтов.
type: docs
weight: 1
url: /ru/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) method


Добавляет дополнительные папки для поиска шрифтов.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Каталоги для чтения дополнительных шрифтов. |
## Примечания



Следующий пример показывает, как загрузить пользовательские шрифты из .TTF 
```cpp
// Путь к каталогу документов.
System::String dataDir = u"C:\\";

// папки для поиска шрифтов
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Загрузить пользовательские шрифты из каталога шрифтов
FontsLoader::LoadExternalFonts(folders);

// Выполнить некоторую работу и отрисовку презентации/слайдов
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Очистить кэш шрифтов
FontsLoader::ClearCache();
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontsLoader](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)