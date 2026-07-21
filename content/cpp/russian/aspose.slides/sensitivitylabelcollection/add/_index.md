---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет метку чувствительности в конец коллекции.
type: docs
weight: 27
url: /ru/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) метод

Добавляет метку чувствительности в конец коллекции.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Идентификатор метки чувствительности. |
| siteId | [System::Guid](../../../system/guid/) | Идентификатор сайта Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Флаг, указывающий, включена ли метка чувствительности. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Метод назначения для метки чувствительности. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) метод


Добавляет [SensitivityLabel](../../sensitivitylabel/) в коллекцию.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Объект [SensitivityLabel](../../sensitivitylabel/), который будет добавлен в конец коллекции. |

### Возвращаемое значение

Индекс, по которому был добавлен [SensitivityLabel](../../sensitivitylabel/).

## См. также

* Перечисление [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [ISensitivityLabel](../../isensitivitylabel/)
* Класс [String](../../../system/string/)
* Класс [Guid](../../../system/guid/)
* Класс [SensitivityLabelCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)