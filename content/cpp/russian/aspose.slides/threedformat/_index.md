---
title: ThreeDFormat
second_title: Справочник API Aspose.Slides для C++
description: Представляет свойства 3-D.
type: docs
weight: 5513
url: /ru/aspose.slides/threedformat/
---
## ThreeDFormat класс

Представляет свойства 3-D.

```cpp
class ThreeDFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IThreeDFormat
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Сравнивает с указанным объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelBottom](./get_bevelbottom/)() override | Возвращает тип нижней 3D фаски. Только для чтения [IShapeBevel](../ishapebevel/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelTop](./get_beveltop/)() override | Возвращает тип верхней 3D фаски. Только для чтения [IShapeBevel](../ishapebevel/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICamera](../icamera/)\> [get_Camera](./get_camera/)() override | Возвращает настройки камеры. Только для чтения [ICamera](../icamera/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ContourColor](./get_contourcolor/)() override | Возвращает цвет контура. Только для чтения [IColorFormat](../icolorformat/). |
| **double** [get_ContourWidth](./get_contourwidth/)() override | Возвращает ширину 3D контура. Читает **double**. |
| **double** [get_Depth](./get_depth/)() override | Возвращает глубину 3D фигуры. Читает **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ExtrusionColor](./get_extrusioncolor/)() override | Возвращает цвет экструзии. Только для чтения [IColorFormat](../icolorformat/). |
| **double** [get_ExtrusionHeight](./get_extrusionheight/)() override | Возвращает высоту эффекта экструзии. Читает **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILightRig](../ilightrig/)\> [get_LightRig](./get_lightrig/)() override | Возвращает тип света. Только для чтения [ILightRig](../ilightrig/). |
| [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() override | Возвращает тип материала. Читает [MaterialPresetType](../materialpresettype/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Возвращает объект Parent_Immediate. Только для чтения [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родительский [IPresentationComponent](../ipresentationcomponent/). Только для чтения [IPresentationComponent](../ipresentationcomponent/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormatEffectiveData](../ithreedformateffectivedata/)\> [GetEffective](./geteffective/)() override | Получает эффективные данные 3-D форматирования с применённым наследованием. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Возвращает хеш-код. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копии. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает общий счётчик ссылок на указанное значение. |
| void [set_ContourWidth](./set_contourwidth/)(**double**) override | Устанавливает ширину 3D контура. Записывает **double**. |
| void [set_Depth](./set_depth/)(**double**) override | Устанавливает глубину 3D фигуры. Записывает **double**. |
| void [set_ExtrusionHeight](./set_extrusionheight/)(**double**) override | Устанавливает высоту эффекта экструзии. Записывает **double**. |
| void [set_Material](./set_material/)([MaterialPresetType](../materialpresettype/)) override | Устанавливает тип материала. Записывает [MaterialPresetType](../materialpresettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент в слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение общего счётчика ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает общий счётчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает общий счётчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Удаляет объект. Освобождает все внутренние структуры данных. |

## Примечания

Следующий пример показывает, как добавить 3D фигуру в PowerPoint [Presentation](../presentation/). 
```cpp
// Создать экземпляр класса Presentation.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Add a shape using AddAutoShape method
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 200.0f, 200.0f);

// Define TextFrame and its properties
shape->get_TextFrame()->set_Text(u"3D");
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(64.0f);

// Define ThreeDFormat Properties
auto threeDFormat = shape->get_ThreeDFormat();
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::OrthographicFront);
threeDFormat->get_Camera()->SetRotation(20.0f, 30.0f, 40.0f);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Flat);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->set_Material(MaterialPresetType::Flat);
threeDFormat->set_ExtrusionHeight(100);
threeDFormat->get_ExtrusionColor()->set_Color(System::Drawing::Color::get_Blue());
slide->GetThumbnail(2.0f, 2.0f)->Save(u"sample_3d.png");

// Save the Presentation file
pres->Save(u"sandbox_3d.pptx", SaveFormat::Pptx);
```
 Следующий пример показывает, как применить градиентный эффект к 3D фигуре в PowerPoint [Presentation](../presentation/). 
```cpp
// Создать экземпляр класса Presentation.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Добавить форму с помощью метода AddAutoShape method
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 250.0f, 250.0f);

// Определить TextFrame и его свойства
shape->get_TextFrame()->set_Text(u"3D Gradient");
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(64.0f);

// Настроить FillFormat.FillType в значение FillType.Gradient и задать свойства градиента
shape->get_FillFormat()->set_FillType(FillType::Gradient);
shape->get_FillFormat()->get_GradientFormat()->get_GradientStops()->Add(0.0f, System::Drawing::Color::get_Blue());
shape->get_FillFormat()->get_GradientFormat()->get_GradientStops()->Add(100.0f, System::Drawing::Color::get_Orange());

// Определить свойства ThreeDFormat
auto threeDFormat = shape->get_ThreeDFormat();
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::OrthographicFront);
threeDFormat->get_Camera()->SetRotation(20.0f, 30.0f, 40.0f);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Flat);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->set_Material(MaterialPresetType::Flat);
threeDFormat->set_ExtrusionHeight(100);
threeDFormat->get_ExtrusionColor()->set_Color(System::Drawing::Color::get_Blue());
slide->GetThumbnail(2.0f, 2.0f)->Save(u"sample_3d.png");

// Сохранить файл Presentation
pres->Save(u"sandbox_3d.pptx", SaveFormat::Pptx);
```
 Следующий пример показывает, как применить 3D эффект к тексту. Для создания 3D текста можно использовать трансформационный эффект WordArt. 
```cpp
// Создать экземпляр класса Presentation.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Добавить форму с помощью метода AddAutoShape method
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 250.0f, 250.0f);

// Определить TextFrame и его свойства
shape->get_TextFrame()->set_Text(u"3D Text");

// Настроить FillFormat.FillType как FillType.NoFill
shape->get_FillFormat()->set_FillType(FillType::NoFill);
shape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::NoFill);

// Настроить Portion в TextFrame и задать свойства PortionFormat
System::SharedPtr<Portion> portion = System::ExplicitCast<Portion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0));
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Pattern);
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->get_ForeColor()->set_Color(System::Drawing::Color::get_DarkOrange());
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->get_BackColor()->set_Color(System::Drawing::Color::get_White());
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->set_PatternStyle(PatternStyle::LargeGrid);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(128.0f);
System::SharedPtr<ITextFrame> textFrame = shape->get_TextFrame();

// Настроить трансформационный эффект WordArt "Arch Up"
textFrame->get_TextFrameFormat()->set_Transform(TextShapeType::ArchUp);

// Определить свойства ThreeDFormat объекта ITextFrame
auto threeDFormat = textFrame->get_TextFrameFormat()->get_ThreeDFormat();
threeDFormat->set_ExtrusionHeight(3.5f);
threeDFormat->set_Depth(3);
threeDFormat->set_Material(MaterialPresetType::Plastic);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Balanced);
threeDFormat->get_LightRig()->SetRotation(0.0f, 0.0f, 40.0f);
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::PerspectiveContrastingRightFacing);
slide->GetThumbnail(2.0f, 2.0f)->Save(u"text3d.png");

// Сохранить файл Presentation.
pres->Save(u"text3d.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Класс [PVIObject](../pviobject/)
* Класс [IThreeDFormat](../ithreedformat/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)