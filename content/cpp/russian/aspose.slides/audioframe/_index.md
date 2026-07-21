---
title: AudioFrame
second_title: Справочник API Aspose.Slides для C++
description: Представляет аудио-клип на слайде.
type: docs
weight: 53
url: /ru/aspose.slides/audioframe/
---
## AudioFrame класс

Represents an audio clip on a slide.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## Методы

| Метод | Описание |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Добавляет новый заполнитель, если его нет, и задаёт свойства заполнителя указанным. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Создаёт и возвращает массив элементов фигуры. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Возвращает значение коррекции фигуры по заданному индексу. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Возвращает коллекцию значений коррекций фигуры. Только для чтения [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Возвращает альтернативный текст, связанный с фигурой. Только для чтения [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Возвращает заголовок альтернативного текста, связанный с фигурой. Только для чтения [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | Возвращает индекс последней дорожки. Только **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | Возвращает время последней дорожки. Только **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | Возвращает индекс начальной дорожки. Только **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | Возвращает время начальной дорожки. Только **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Только [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Получает коллекцию закрытых субтитров, связанных с аудио-кадром. Это свойство только для чтения и возвращает [ICaptionsCollection](../icaptionscollection/), содержащий все дорожки субтитров. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Возвращает количество точек подключения на фигуре. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Возвращает пользовательские данные фигуры. Только для чтения [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Возвращает объект [EffectFormat](../effectformat/), содержащий пиксельные эффекты, применённые к фигуре. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств эффектов. Только для чтения [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | Определяет, встроен ли звук в презентацию. Только для чтения **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | Возвращает встроенный аудио-объект. Только [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | Задаёт длительность начального появления медиа в миллисекундах. Только **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | Задаёт длительность конечного исчезновения медиа в миллисекундах. Только **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Возвращает объект [FillFormat](../fillformat/), содержащий свойства заливки фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств заливки. Только для чтения [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Возвращает свойства кадра фигуры. Только [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Получает высоту фигуры в пунктах. Только **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Определяет, скрыта ли фигура. Только **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Определяет, скрыт ли [AudioFrame](./). Только **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Возвращает гиперссылку, определённую для клика мышью. Только [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Возвращает менеджер гиперссылок. Только для чтения [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Возвращает гиперссылку, определённую для наведения мыши. Только [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Определяет, является ли [PictureFrame](../pictureframe/) объектом Cameo. Только **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Получает параметр «Отметить как декоративный». Запись/чтение **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Определяет, сгруппирована ли фигура. Только для чтения **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Определяет, является ли фигура TextHolder_PPT. Только для чтения **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Возвращает объект [LineFormat](../lineformat/), содержащий свойства форматирования линий фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств линии. Только для чтения [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Возвращает имя аудио-файла, связанного с [AudioFrame](./). Только [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Возвращает имя фигуры. Не должно быть null. При необходимости используйте пустую строку. Только [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Возвращает уникальный идентификатор слайд-уровня, который остаётся постоянным в течение жизненного цикла фигуры и позволяет PowerPoint или коду interop надёжно ссылаться на фигуру из любой части документа. Только для чтения **uint32_t**. Смотрите также [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Возвращает родительский объект [GroupShape](../groupshape/), если фигура сгруппирована. В противном случае возвращает null. Только для чтения [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Возвращает объект [PictureFillFormat](../picturefillformat/) для рамки изображения. Только для чтения [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Возвращает блокировки фигуры. Только для чтения [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Возвращает заполнитель для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | Определяет, воспроизводится ли аудио на всех слайдах. Только **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Определяет, зациклен ли аудио. Только **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Возвращает режим воспроизведения аудио. Только [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Возвращает родительскую презентацию слайда. Только для чтения [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Возвращает необработанные свойства кадра фигуры. Только [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Возвращает масштаб высоты (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100 %. Только **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Возвращает масштаб ширины (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100 %. Только **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | Определяет, автоматически ли аудио перематывается к началу после воспроизведения. Только **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Возвращает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение — вращение по часовой стрелке; отрицательное — против часовой стрелки. Только **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Возвращает блокировки фигуры. Только для чтения [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Возвращает объект стиля фигуры. Только для чтения [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Возвращает родительский слайд фигуры. Только для чтения [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Возвращает объект [ThreeDFormat](../threedformat/), содержащий свойства 3-d эффекта для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет 3-d свойств. Только для чтения [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Задаёт длительность, которую нужно удалить с конца медиа при воспроизведении, в миллисекундах. Только **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Задаёт длительность, которую нужно удалить с начала медиа при воспроизведении, в миллисекундах. Только **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Возвращает внутренний идентификатор, привязанный к презентации, предназначенный для использования адд-инами или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения **uint32_t**. Смотрите также [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Возвращает громкость аудио. Только [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | Возвращает громкость аудио в процентах. Только **float**. |
| **float** [get_Width](../shape/get_width/)() override | Получает ширину фигуры в пунктах. Только **float**. |
| **float** [get_X](../shape/get_x/)() override | Получает координату x верхнего левого угла фигуры в пунктах. Только **float**. |
| **float** [get_Y](../shape/get_y/)() override | Получает координату y верхнего левого угла фигуры в пунктах. Только **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру в самом заднем слое, а Shapes[Shapes.Count - 1] — в самом переднем. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Возвращает базовую фигуру-заполнитель (фигуру из макета и/или главного слайда, от которой наследуется текущая фигура). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Возвращает копию пути геометрической фигуры. Координаты относительны к левому верхнему углу фигуры. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Возвращает миниатюру фигуры. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Получает визуальные границы фигуры, рассчитанные по её отрисованному содержимому. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, является ли объект экземпляром типа, описанного targetType. Аналог оператора C# `is`. |
| void [Lock](../../system/object/lock/)() | Реализует оператор C# lock() блокировки. Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект-значение со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Объявляет, что эта фигура не является заполнителем. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Устанавливает альтернативный текст, связанный с фигурой. Запись [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Устанавливает заголовок альтернативного текста, связанный с фигурой. Запись [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | Устанавливает индекс последней дорожки. Запись **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | Устанавливает время последней дорожки. Запись **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | Устанавливает индекс начальной дорожки. Запись **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | Устанавливает время начальной дорожки. Запись **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Запись [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Устанавливает встроенный аудио-объект. Запись [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | Задаёт длительность начального появления медиа в миллисекундах. Запись **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | Задаёт длительность конечного исчезновения медиа в миллисекундах. Запись **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Устанавливает свойства кадра фигуры. Запись [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Устанавливает высоту фигуры в пунктах. Запись **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Определяет, скрыта ли фигура. Запись **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Определяет, скрыт ли [AudioFrame](./). Запись **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Устанавливает гиперссылку для клика мышью. Запись [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Устанавливает гиперссылку для наведения мыши. Запись [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Устанавливает параметр «Отметить как декоративный». Запись/чтение **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Устанавливает имя аудио-файла, связанного с [AudioFrame](./). Запись [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Устанавливает имя фигуры. Не должно быть null. При необходимости используйте пустую строку. Запись [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | Определяет, воспроизводится ли аудио на всех слайдах. Запись **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Определяет, зациклен ли аудио. Запись **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | Устанавливает режим воспроизведения аудио. Запись [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Устанавливает необработанные свойства кадра фигуры. Запись [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Задаёт масштаб высоты (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100 %. Запись **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Задаёт масштаб ширины (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100 %. Запись **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | Определяет, автоматически ли аудио перематывается к началу после воспроизведения. Запись **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Задаёт количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение — вращение по часовой стрелке; отрицательное — против часовой стрелки. Запись **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Задаёт длительность, которую нужно удалить с конца медиа при воспроизведении, в миллисекундах. Запись **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Задаёт длительность, которую нужно удалить с начала медиа при воспроизведении, в миллисекундах. Запись **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Устанавливает громкость аудио. Запись [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | Устанавливает громкость аудио в процентах. Запись **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Задаёт ширину фигуры в пунктах. Запись **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Задаёт координату x верхнего левого угла фигуры в пунктах. Запись **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Задаёт координату y верхнего левого угла фигуры в пунктах. Запись **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Обновляет геометрию фигуры из объекта [IGeometryPath](../igeometrypath/). Координаты должны быть относительны к левому верхнему углу фигуры. Меняет тип фигуры ([ShapeType](../shapetype/)) на [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Обновляет геометрию фигуры из массива [IGeometryPath](../igeometrypath/). Координаты должны быть относительны к левому верхнему углу фигуры. Меняет тип фигуры ([ShapeType](../shapetype/)) на [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает {{n}}-й шаблонный аргумент как слабую ссылку (а не shared). Позволяет переключать ссылки в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не должно вызываться напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не должно вызываться напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не должно вызываться напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не должно вызываться напрямую; используйте умные указатели или ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Сохраняет содержимое [Shape](../shape/) как файл SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Сохраняет содержимое [Shape](../shape/) как файл SVG. |
| virtual  [~Object](../../system/object/~object/)() | Удаляет объект. Освобождает все внутренние структуры данных. |
## Примечания

The following examples shows how to change [Audio](../audio/) Play Options. 
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Получает форму AudioFrame
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Устанавливает режим воспроизведения на воспроизведение по щелчку
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Устанавливает громкость на низкую
audioFrame->set_Volume(AudioVolumeMode::Low);
// Устанавливает воспроизведение аудио на всех слайдах
audioFrame->set_PlayAcrossSlides(true);
// Отключает зацикливание аудио
audioFrame->set_PlayLoopMode(false);
// Скрывает AudioFrame во время показа слайдов
audioFrame->set_HideAtShowing(true);
// Перематывает аудио к началу после воспроизведения
audioFrame->set_RewindAudio(true);
// Сохраняет файл PowerPoint на диск
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [PictureFrame](../pictureframe/)
* Класс [IAudioFrame](../iaudioframe/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)