---
title: IAudioFrame
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++
description: يمثل مقطعًا صوتيًا على شريحة.
type: docs
weight: 1353
url: /ar/aspose.slides/iaudioframe/
---
## IAudioFrame فئة

Represents an audio clip on a slide.

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | يضيف عنصر نائب جديد إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | ينشئ ويعيد مصفوفة من عناصر الشكل. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا للمعيار IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا للمعيار IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | يعيد قيمة تعديل الشكل عند الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | يعيد مجموعة من قيم تعديل الشكل. قراءة فقط [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | يعيد النص البديل المرتبط بالشكل. قراءة [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | يعيد عنوان النص البديل المرتبط بالشكل. قراءة [System::String](../../system/string/). |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | يعيد فهرس المسار الأخير. قراءة **int32_t**. |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | يعيد وقت المسار الأخير. قراءة **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | يعيد فهرس بداية المسار. قراءة **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | يعيد وقت بداية المسار. قراءة **int32_t**. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | الخاصية تحدد كيفية عرض الشكل في وضع اللونين الأسود والأبيض.. قراءة [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | يحصل على مجموعة الشروح المغلقة المرتبطة بإطار الصوت. هذه الخاصية للقراءة فقط وتعيد [ICaptionsCollection](../icaptionscollection/) يحتوي على جميع مسارات الشروح. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | يعيد عدد مواقع الاتصال على الشكل. قراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | يعيد بيانات مخصصة للشكل. قراءة فقط [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | يعيد كائن [EffectFormat](../effectformat/) الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. قراءة فقط [IEffectFormat](../ieffectformat/). |
| virtual **bool** [get_Embedded](./get_embedded/)() | يحدد ما إذا كان الصوت مدمجًا في العرض التقديمي. قراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | يعيد كائن الصوت المدمج. قراءة [IAudio](../iaudio/). |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | يحدد مدة الوقت للظهور التدريجي الأولي للوسائط بالمللي ثانية. قراءة **float**. |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | يحدد مدة الوقت للظهور التدريجي النهائي للوسائط بالمللي ثانية. قراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | يعيد كائن [FillFormat](../fillformat/) الذي يحتوي على خصائص تنسيق التعبئة لشكل. قراءة فقط [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | يعيد خصائص إطار الشكل. قراءة [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | يحصل على ارتفاع الشكل، مقاسًا بالنقاط. قراءة **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | يحدد ما إذا كان الشكل مخفيًا. قراءة **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | يحدد ما إذا كان [AudioFrame](../audioframe/) مخفيًا. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | يعيد الرابط التشعبي المحدد للنقر بالماوس. قراءة [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدير الروابط التشعبية قراءة فقط [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | يعيد الرابط التشعبي المحدد للتمرير فوق الماوس. قراءة [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | يحصل على خيار 'وضع علامة كزخرفة' قراءة/كتابة **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | يحدد ما إذا كان الشكل مجموعة. قراءة فقط **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | يحدد ما إذا كان الشكل TextHolder. قراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | يعيد كائن [LineFormat](../lineformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. قراءة فقط [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | يعيد اسم ملف الصوت المرتبط بـ [AudioFrame](../audioframe/). قراءة [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | يعيد اسم الشكل. قراءة [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | يعيد معرفًا فريدًا بنطاق الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل بثقة من أي مكان في المستند. قراءة فقط **uint32_t**. انظر أيضًا [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | يعيد كائن [GroupShape](../groupshape/) الأب إذا كان الشكل مجموعة. وإلا يعيد null. قراءة فقط [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | يعيد كائن [PictureFillFormat](../picturefillformat/) لإطار الصورة. قراءة فقط [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | يعيد أقفال [PictureFrame](../pictureframe/). قراءة فقط [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | يعيد العنصر النائب لشكل. قراءة فقط [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | يحدد ما إذا كان الصوت يُشغل عبر الشرائح. قراءة **bool**. |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | يحدد ما إذا كان الصوت متكررًا. قراءة **bool**. |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | يعيد وضع تشغيل الصوت. قراءة [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. قراءة فقط [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | يعيد خصائص إطار الشكل الخام. قراءة [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | يعيد مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. قراءة **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | يعيد مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. قراءة **float**. |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | يحدد ما إذا كان الصوت يُعاد تشغيله تلقائيًا إلى البداية بعد التشغيل. قراءة **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | يعيد عدد الدرجات التي يدور فيها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. قراءة **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | يعيد أقفال الشكل. قراءة فقط [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | يعيد كائن نمط الشكل. قراءة فقط [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | يعيد نوع إعداد الهندسة المسبق. ملاحظة: عند تغيير القيمة ستُعاد جميع قيم التعديل إلى قيمها الافتراضية. قراءة [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. قراءة فقط [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | يعيد كائن [ThreeDFormat](../threedformat/) الذي يحتوي على خصائص تنسيق الخط لشكل. قراءة فقط [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | يحدد مدة الوقت التي تُزال من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. قراءة **float**. |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | يحدد مدة الوقت التي تُزال من بداية الوسائط أثناء التشغيل، بالمللي ثانية. قراءة **float**. |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | يعيد معرفًا داخليًا بنطاق العرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو الكود الآخر. لأن هذا القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط **uint32_t**. انظر أيضًا [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | يعيد حجم الصوت. قراءة [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | يعيد حجم الصوت كنسبة مئوية. قراءة **float**. |
| virtual **float** [get_Width](../ishape/get_width/)() | يحصل على عرض الشكل، مقاسًا بالنقاط. قراءة **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | يحصل على إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | يحصل على إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | يعيد موضع الشكل في ترتيب z. Shapes[0] يعيد الشكل في خلفية ترتيب z، وShapes[Shapes.Count - 1] يعيد الشكل في مقدمة ترتيب z. قراءة فقط **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الأم التي يرث منها الشكل الحالي). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | يعيد نسخة من مسار الشكل الهندسي. الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن من تجزئة الكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | يعيد صورة مصغرة للشكل. نوع حدود الصورة المصغرة [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) يُستخدم افتراضيًا. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | يعيد صورة مصغرة للشكل. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثالًا للنوع الموصوف بـ targetType. تماثل عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفّذ بيان القفل C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن من استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يتهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مشغل الإسناد. لا ينسخ أي شيء فعليًا، فقط يتهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائنًا من النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | يعرّف أن هذا الشكل ليس عنصرًا نائبًا. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | يضبط النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | يضبط عنوان النص البديل المرتبط بالشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | يضبط فهرس المسار الأخير كتابة **int32_t**. |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | يضبط وقت المسار الأخير كتابة **int32_t**. |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | يضبط فهرس بداية المسار كتابة **int32_t**. |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | يضبط وقت بداية المسار كتابة **int32_t**. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | الخاصية تحدد كيفية عرض الشكل في وضع اللونين الأسود والأبيض.. كتابة [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | يضبط كائن الصوت المدمج. كتابة [IAudio](../iaudio/). |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | يحدد مدة الوقت للظهور التدريجي الأولي للوسائط بالمللي ثانية. كتابة **float**. |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | يحدد مدة الوقت للظهور التدريجي النهائي للوسائط بالمللي ثانية. كتابة **float**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | يضبط خصائص إطار الشكل. كتابة [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | يضبط ارتفاع الشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | يحدد ما إذا كان الشكل مخفيًا. كتابة **bool**. |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | يحدد ما إذا كان [AudioFrame](../audioframe/) مخفيًا. كتابة **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الرابط التشعبي المحدد للنقر بالماوس. كتابة [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | يضبط الرابط التشعبي المحدد للتمرير فوق الماوس. كتابة [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | يضبط خيار 'وضع علامة كزخرفة' قراءة/كتابة **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | يضبط اسم ملف الصوت المرتبط بـ [AudioFrame](../audioframe/). كتابة [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | يضبط اسم الشكل. كتابة [System::String](../../system/string/). |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | يحدد ما إذا كان الصوت يُشغل عبر الشرائح. كتابة **bool**. |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | يحدد ما إذا كان الصوت متكررًا. كتابة **bool**. |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | يضبط وضع تشغيل الصوت. كتابة [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | يضبط خصائص إطار الشكل الخام. كتابة [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | يضبط مقياس الارتفاع (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. كتابة **float**. |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | يضبط مقياس العرض (نسبة إلى حجم الصورة الأصلي) لإطار الصورة. القيمة 1.0 تعادل 100٪. كتابة **float**. |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | يحدد ما إذا كان الصوت يُعاد تشغيله تلقائيًا إلى البداية بعد التشغيل. كتابة **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | يضبط عدد الدرجات التي يدور فيها الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. كتابة **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | يضبط نوع إعداد الهندسة المسبق. ملاحظة: عند تغيير القيمة ستُعاد جميع قيم التعديل إلى قيمها الافتراضية. كتابة [Slides::ShapeType](../shapetype/). |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | يحدد مدة الوقت التي تُزال من نهاية الوسائط أثناء التشغيل، بالمللي ثانية. كتابة **float**. |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | يحدد مدة الوقت التي تُزال من بداية الوسائط أثناء التشغيل، بالمللي ثانية. كتابة **float**. |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | يضبط حجم الصوت. كتابة [AudioVolumeMode](../audiovolumemode/). |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | يضبط حجم الصوت كنسبة مئوية. كتابة **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | يضبط عرض الشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | يضبط إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | يضبط إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. كتابة **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | يُحدّث هندسة الشكل من كائن [IGeometryPath](../igeometrypath/). الإحداثيات يجب أن تكون نسبية إلى الزاوية العلوية اليسرى للشكل. يغيّر نوع الشكل ([ShapeType](../shapetype/)) إلى [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | يُحدّث هندسة الشكل من مصفوفة [IGeometryPath](../igeometrypath/). الإحداثيات يجب أن تكون نسبية إلى الزاوية العلوية اليسرى للشكل. يغيّر نوع الشكل ([ShapeType](../shapetype/)) إلى [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يحدد الوسيط القالب ال n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استبدل ذلك بالمؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استبدل ذلك بالمؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن من تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ إنشاء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ بيان القفل C# lock() لإلغاء القفل. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استبدل ذلك بالمؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استبدل ذلك بالمؤشرات الذكية أو ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | يحفظ محتوى [Shape](../shape/) كملف SVG. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## راجع أيضًا

* فئة [IPictureFrame](../ipictureframe/)
* مساحة الأسماء [Aspose::Slides](../)
* مكتبة [Aspose.Slides](../../)