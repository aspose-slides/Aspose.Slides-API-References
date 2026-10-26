---
title: AddGroupShape()
second_title: Aspose.Slides для C++ — справочник API
description: Создаёт новую пустую групповую форму и добавляет её в конец коллекции фигур. Рамка группы автоматически подстраивается под любые добавленные в неё фигуры.
type: docs
weight: 391
url: /ru/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() метод

Создаёт новую пустую групповую форму и добавляет её в конец коллекции фигур. Рамка группы будет автоматически подстраиваться под любые добавленные в неё фигуры.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### Возвращаемое значение

Новосозданный [IGroupShape](../../igroupshape/).

## Замечания

В следующем примере показано, как добавить групповую форму на слайд PowerPoint [Presentation](../../presentation/).

```cpp
// Создать экземпляр класса Presentation
auto pres = System::MakeObject<Presentation>();

// Получить первый слайд
auto slide = pres->get_Slides()->idx_get(0);
// Доступ к коллекции фигур слайдов
auto slideShapes = slide->get_Shapes();
// Добавление групповой формы на слайд
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Добавление фигур внутрь добавленной групповой формы
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Добавление рамки групповой формы
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Записать файл PPTX на диск
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) метод

Создаёт новую групповую форму, преобразует указанное SVG-изображение в отдельные фигуры и добавляет получившуюся группу в конец коллекции фигур.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/), содержащий векторный контент для преобразования в фигуры. |
| x | **float** | Координата x рамки группы в пунктах. |
| y | **float** | Координата y рамки группы в пунктах. |
| width | **float** | Ширина рамки группы в пунктах. |
| height | **float** | Высота рамки группы в пунктах. |

### Возвращаемое значение

Новосозданный [IGroupShape](../../igroupshape/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [ShapeCollection](../)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)