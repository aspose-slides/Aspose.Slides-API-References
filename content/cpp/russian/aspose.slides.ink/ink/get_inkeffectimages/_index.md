---
title: get_InkEffectImages()
second_title: Aspose.Slides для C++ справочник API
description: Получает коллекцию пользовательских изображений, используемых для имитации визуальных эффектов кистей чернил. Эти изображения используются при рендеринге чернил с конкретными значениями InkEffectType, такими как Galaxy, Rainbow и т.д. Предоставляя свои изображения, вы можете контролировать, как отображается каждый эффект чернил.
type: docs
weight: 14
url: /ru/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() метод

Получает коллекцию пользовательских изображений, используемых для имитации визуальных эффектов кистей чернила. Эти изображения используются при рендеринге чернил с определенными значениями [InkEffectType](../../inkeffecttype/), такими как Galaxy, Rainbow и т.д. Предоставляя свои изображения, вы можете контролировать, как каждый эффект чернил выглядит.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Примечания

Это свойство позволяет заменять текстуры эффектов чернил по умолчанию пользовательскими, что особенно полезно, когда стандартные ресурсы ограничены лицензией или недоступны во время выполнения.

Каждая запись в словаре должна связывать значение [InkEffectType](../../inkeffecttype/) с соответствующим объектом [IImage](../../../aspose.slides/iimage/) (например, Bitmap или интерфейс изображения **Aspose**).

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## См. также

* Перечисление [InkEffectType](../../inkeffecttype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IDictionary](../../../system.collections.generic/idictionary/)
* Класс [IImage](../../../aspose.slides/iimage/)
* Класс [Ink](../)
* Пространство имен [Aspose::Slides::Ink](../../)
* Библиотека [Aspose.Slides](../../../)