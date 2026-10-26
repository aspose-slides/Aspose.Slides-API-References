---
title: Add()
second_title: Aspose.Slides для C++ Справка по API
description: Добавляет метку чувствительности в конец коллекции.
type: docs
weight: 27
url: /ru/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) метод


Добавляет метку чувствительности в конец коллекции.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Идентификатор метки чувствительности. |
| siteId | [System::Guid](../../../system/guid/) | Идентификатор сайта Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Флаг, указывающий, включена ли метка чувствительности. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Метод назначения метки чувствительности. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) метод


Добавляет [SensitivityLabel](../../sensitivitylabel/) в коллекцию.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Объект [SensitivityLabel](../../sensitivitylabel/), добавляемый в конец коллекции. |

### Возвращаемое значение

Индекс, по которому был добавлен [SensitivityLabel](../../sensitivitylabel/).

## См. также

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISensitivityLabel](../../isensitivitylabel/)
* Класс [String](../../../system/string/)
* Класс [Guid](../../../system/guid/)
* Класс [ISensitivityLabelCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)