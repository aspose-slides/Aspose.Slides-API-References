---
title: Control
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет элемент управления ActiveX.
type: docs
weight: 2540
url: /ru/net/aspose.slides/control/
---
## Control class

Представляет элемент управления ActiveX.

```csharp
public class Control : DomObject<ControlCollection>, IControl
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActiveXControlBinary](../../aspose.slides/control/activexcontrolbinary) { get; } | Задает сохраняемость элемента управления ActiveX, когда для сохранения используется метод PersistStream, PersistStreamInit или PersistStorage. |
| [ClassId](../../aspose.slides/control/classid) { get; set; } | Получает идентификатор класса этого элемента управления. Только чтениеGuid. |
| [Frame](../../aspose.slides/control/frame) { get; set; } | Возвращает или устанавливает кадр элемента управления. Чтение/запись[`IShapeFrame`](../ishapeframe). |
| [Name](../../aspose.slides/control/name) { get; set; } | Получает или задает имя этого элемента управления. Чтение/записьString. |
| [Persistence](../../aspose.slides/control/persistence) { get; } | Получает метод, используемый для хранения свойств элемента управления ActiveX. Только чтение[`PersistenceType`](../persistencetype). |
| [Properties](../../aspose.slides/control/properties) { get; } | Возвращает набор свойств ActiveX.  Примечание:Aspose.Slides поддерживает только свойства ActiveX на основе XML. Если свойства хранятся в двоичном формате, это свойство возвращает значение null. Только чтение[`IControlPropertiesCollection`](../icontrolpropertiescollection). |
| [SubstitutePictureFormat](../../aspose.slides/control/substitutepictureformat) { get; } | Возвращает объект свойств заливки управляющего изображения. Только для чтения[`IPictureFillFormat`](../ipicturefillformat). |

### Смотрите также

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [ControlCollection](../controlcollection)
* interface [IControl](../icontrol)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->