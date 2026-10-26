---
title: AudioFrame
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل مقطعًا صوتيًا على شريحة.
type: docs
weight: 53
url: /ar/aspose.slides/audioframe/
---
## AudioFrame فئة

يمثل مقطع صوتي على شريحة.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | ينشئ ويعيد مصفوفة عناصر الشكل. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمة NaN مساوية لقيمة NaN أخرى على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس موازيًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمة NaN مساوية لقيمة NaN أخرى على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس موازيًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | يرجع قيمة تعديل الشكل عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | يرجع مجموعة من قيم تعديل الشكل. قراءة فقط [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | يرجع النص البديل المرتبط بالشكل. قراءة [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | يرجع عنوان النص البديل المرتبط بالشكل. قراءة [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | يرجع فهرس المسار الأخير. قراءة **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | يرجع وقت المسار الأخير. قراءة **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | يرجع فهرس بداية المسار. قراءة **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | يرجع وقت بداية المسار. قراءة **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | تحدد الخاصية كيف سيُعرض الشكل في وضع العرض بالأبيض والأسود. قراءة [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | يحصل على مجموعة الترجمات المغلقة المرتبطة بإطار الصوت. هذه الخاصية قراءة فقط وتُعيد [ICaptionsCollection](../icaptionscollection/) يحتوي على جميع مسارات الترجمات. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | يرجع عدد نقاط الاتصال على الشكل. قراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | يرجع البيانات المخصصة للشكل. قراءة فقط [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | يرجع كائن [EffectFormat](../effectformat/) الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص تأثير. قراءة فقط [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | يحدد ما إذا كان الصوت مدمجًا في العرض التقديمي. قراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | يرجع كائن الصوت المدمج. قراءة [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | يحدد مدة التلاشي الأولي للوسائط بالمليثانية. قراءة **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | يحدد مدة التلاشي النهائي للوسائط بالمليثانية. قراءة **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | يرجع كائن [FillFormat](../fillformat/) الذي يحتوي على خصائص تنسيق التعبئة للشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص تعبئة. قراءة فقط [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | يرجع خصائص إطار الشكل. قراءة [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. قراءة **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | يحدد ما إذا كان الشكل مخفيًا. قراءة **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | يحدد ما إذا كان [AudioFrame](./) مخفيًا. قراءة **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | يرجع الرابط التشعبي المحدد للنقر بالماوس. قراءة [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | يرجع مدير الروابط التشعبية. قراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | يرجع الرابط التشعبي المحدد لتمرير الماوس. قراءة [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | يحدد ما إذا كان [PictureFrame](../pictureframe/) كائن Cameo أم لا. قراءة فقط **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | يحصل على خيار 'وضع علامة كديكوري' قراءة/كتابة **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | يحدد ما إذا كان الشكل مجموعة. قراءة فقط **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | يحدد ما إذا كان الشكل TextHolder_PPT. قراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | يرجع كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط للشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص الخط. قراءة فقط [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | يرجع اسم ملف صوتي مرتبط بـ [AudioFrame](./). قراءة [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | يرجع اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. قراءة [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | يرجع معرفًا فريدًا على مستوى الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالرجوع إلى الشكل من أي مكان في المستند. قراءة فقط **uint32_t**. انظر أيضًا [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | يرجع كائن [GroupShape](../groupshape/) الأب إذا كان الشكل مجموعة. وإلا يُعيد null. قراءة فقط [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | يرجع كائن [PictureFillFormat](../picturefillformat/) لإطار الصورة. قراءة فقط [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | يرجع أقفال الشكل. قراءة فقط [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | يرجع العنصر النائب للشكل. يُعيد null إذا لم يكن للشكل عنصر نائب. قراءة فقط [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | يحدد ما إذا كان الصوت يُشغل عبر الشرائح. قراءة **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | يحدد ما إذا كان الصوت مكررًا. قراءة **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | يرجع وضع تشغيل الصوت. قراءة [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | يرجع عرض الشرائح الأب لشريحة. قراءة فقط [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | يرجع خصائص إطار الشكل الخام. قراءة [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | يرجع مقياس ارتفاع إطار الصورة (نسبةً إلى حجم الصورة الأصلي). القيمة 1.0 تمثل 100٪. قراءة **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | يرجع مقياس عرض إطار الصورة (نسبةً إلى حجم الصورة الأصلي). القيمة 1.0 تمثل 100٪. قراءة **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | يحدد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. قراءة **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | يرجع عدد الدرجات التي يدور فيها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقرب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقرب الساعة. قراءة **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | يرجع أقفال الشكل. قراءة فقط [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | يرجع كائن نمط الشكل. قراءة فقط [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | يرجع الشريحة الأصلية للشكل. قراءة فقط [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | يرجع كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص التأثير ثلاثي الأبعاد للشكل. ملاحظة: قد يُعيد null لأنواع معينة من الأشكال التي لا تمتلك خصائص ثلاثية الأبعاد. قراءة فقط [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | يحدد مدة الزمن التي تُزال من نهاية الوسائط أثناء التشغيل بالمليثانية. قراءة **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | يحدد مدة الزمن التي تُزال من بداية الوسائط أثناء التشغيل بالمليثانية. قراءة **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | يرجع معرفًا داخليًا على مستوى العرض مخصصًا للاستخدام من قبل الإضافات أو الكود الآخر. نظرًا لأن هذه القيمة يمكن أن يعيد تعيينها المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط **uint32_t**. انظر أيضًا [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | يرجع مستوى صوت الصوت. قراءة [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | يرجع مستوى صوت الصوت كنسبة مئوية. قراءة **float**. |
| **float** [get_Width](../shape/get_width/)() override | يحصل على عرض الشكل، مقاسًا بالنقاط. قراءة **float**. |
| **float** [get_X](../shape/get_x/)() override | يحصل على إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة **float**. |
| **float** [get_Y](../shape/get_y/)() override | يحصل على إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | يرجع موضع الشكل في ترتيب z. Shapes[0] يُعيد الشكل الموجود في مؤخرة ترتيب z، و Shapes[Shapes.Count - 1] يُعيد الشكل الموجود في مقدمة ترتيب z. قراءة فقط **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | يرجع شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عدّاد المرجع المرتبط بالكائن. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | يرجع نسخة من مسار الشكل الهندسي. الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | يرجع صورة مصغرة للشكل. نوع حدود الصورة المصغرة [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) يُستخدم افتراضيا. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | يرجع صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | يحصل على الحدود البصرية للشكل محسوبة من محتواه المرسوم. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يُمثل نسخة من النوع الموضّح بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تطبق قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يُهيّء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيء فعليًا، بل يهيّء كائنًا جديدًا ويُمكّن بناء نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيء فعليًا، بل يهيّء كائنًا جديدًا ويُمكّن بناء نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | يضبط النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | يضبط عنوان النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | يضبط فهرس المسار الأخير. كتابة **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | يضبط وقت المسار الأخير. كتابة **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | يضبط فهرس بداية المسار. كتابة **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | يضبط وقت بداية المسار. كتابة **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | تحدد الخاصية كيف سيُعرض الشكل في وضع العرض بالأبيض والأسود. كتابة [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | يضبط كائن الصوت المدمج. كتابة [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | يحدد مدة التلاشي الأولي للوسائط بالمليثانية. كتابة **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | يحدد مدة التلاشي النهائي للوسائط بالمليثانية. كتابة **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل. كتابة [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | يضبط ارتفاع الشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | يحدد ما إذا كان الشكل مخفيًا. كتابة **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | يحدد ما إذا كان [AudioFrame](./) مخفيًا. كتابة **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الرابط التشعبي المحدد للنقر بالماوس. كتابة [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | يضبط الرابط التشعبي المحدد لتمرير الماوس. كتابة [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | يضبط خيار 'وضع علامة كديكوري' قراءة/كتابة **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | يضبط اسم ملف الصوت المرتبط بـ [AudioFrame](./). كتابة [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | يضبط اسم الشكل. يجب ألا يكون فارغًا. استخدم قيمة سلسلة فارغة إذا لزم الأمر. كتابة [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | يحدد ما إذا كان الصوت يُشغل عبر الشرائح. كتابة **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | يحدد ما إذا كان الصوت مكررًا. كتابة **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | يضبط وضع تشغيل الصوت. كتابة [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | يضبط خصائص إطار الشكل الخام. كتابة [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | يضبط مقياس ارتفاع إطار الصورة (نسبةً إلى حجم الصورة الأصلي). القيمة 1.0 تمثل 100٪. كتابة **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | يضبط مقياس عرض إطار الصورة (نسبةً إلى حجم الصورة الأصلي). القيمة 1.0 تمثل 100٪. كتابة **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | يحدد ما إذا كان الصوت يُعاد تلقائيًا إلى البداية بعد التشغيل. كتابة **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | يضبط عدد الدرجات التي يدور فيها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقرب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقرب الساعة. كتابة **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | يحدد مدة الزمن التي تُزال من نهاية الوسائط أثناء التشغيل بالمليثانية. كتابة **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | يحدد مدة الزمن التي تُزال من بداية الوسائط أثناء التشغيل بالمليثانية. كتابة **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | يضبط مستوى صوت الصوت. كتابة [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | يضبط مستوى صوت الصوت كنسبة مئوية. كتابة **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | يضبط عرض الشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_X](../shape/set_x/)(**float**) override | يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | يحدّث هندسة الشكل من كائن [IGeometryPath](../igeometrypath/). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. يغيّر نوع الشكل ([ShapeType](../shapetype/)) إلى [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | يحدّث هندسة الشكل من مصفوفة [IGeometryPath](../igeometrypath/). يجب أن تكون الإحداثيات نسبية للزاوية العلوية اليسرى للشكل. يغيّر نوع الشكل ([ShapeType](../shapetype/)) إلى [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويُعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُحرر جميع هياكل البيانات الداخلية. |

## ملاحظات

توضح الأمثلة التالية كيفية تغيير خيارات التشغيل [Audio](../audio/).  
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Gets the AudioFrame shape
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Sets the Play mode to play on click
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Sets the volume to Low
audioFrame->set_Volume(AudioVolumeMode::Low);
// Sets the audio to play across slides
audioFrame->set_PlayAcrossSlides(true);
// Disables loop for the audio
audioFrame->set_PlayLoopMode(false);
// Hides the AudioFrame during the slide show
audioFrame->set_HideAtShowing(true);
// Rewinds the audio to start after playing
audioFrame->set_RewindAudio(true);
// Saves the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* فئة [PictureFrame](../pictureframe/)
* فئة [IAudioFrame](../iaudioframe/)
* نطاق [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)