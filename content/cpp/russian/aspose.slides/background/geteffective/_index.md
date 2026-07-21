---
title: GetEffective()
second_title: Справочник API Aspose.Slides для C++
description: Получает эффективные данные фона с учётом наследования.
type: docs
weight: 118
url: /ru/aspose.slides/background/geteffective/
---
## Background::GetEffective() метод


Получает эффективные данные фона с учётом наследования.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### Возвращаемое значение

Экземпляр [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## Примечания



Этот пример демонстрирует получение эффективных свойств фона. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Класс [Background](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)