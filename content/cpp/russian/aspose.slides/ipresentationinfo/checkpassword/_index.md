---
title: CheckPassword()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет, правильный ли пароль для презентации, защищённой открытым паролем.
type: docs
weight: 53
url: /ru/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) метод


Проверяет, правильный ли пароль для презентации, защищённой открытым паролем.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Пароль для проверки. |

### Возвращаемое значение

True если презентация защищена открытым паролем и пароль правильный, иначе false.
## Примечания



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



Когда пароль равен null или пустой, этот метод возвращает false. 
## См. также

* Класс [String](../../../system/string/)
* Класс [IPresentationInfo](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)