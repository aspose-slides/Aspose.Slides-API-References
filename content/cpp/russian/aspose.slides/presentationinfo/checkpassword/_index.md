---
title: CheckPassword()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, правильный ли пароль для презентации, защищённой открытым паролем.
type: docs
weight: 53
url: /ru/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) метод

Проверяет, является ли пароль правильным для презентации, защищённой открытым паролем.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Пароль для проверки. |

### Возвращаемое значение

True если презентация защищена открытым паролем и пароль правильный, иначе false.

### Примечания

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Когда пароль равен null или пуст, этот метод возвращает false.

### См. также

* Класс [String](../../../system/string/)
* Класс [PresentationInfo](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)