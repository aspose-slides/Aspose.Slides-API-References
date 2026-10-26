---
title: ThreeDFormat
second_title: Aspose.Slides for C++ API リファレンス
description: 3-D プロパティを表します。
type: docs
weight: 5513
url: /ja/aspose.slides/threedformat/
---
## ThreeDFormat クラス


3-D プロパティを表します。

```cpp
class ThreeDFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IThreeDFormat
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定されたオブジェクトと比較します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelBottom](./get_bevelbottom/)() override | 底部 3D ベベルのタイプを返します。読み取り専用 [IShapeBevel](../ishapebevel/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelTop](./get_beveltop/)() override | 上部 3D ベベルのタイプを返します。読み取り専用 [IShapeBevel](../ishapebevel/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICamera](../icamera/)\> [get_Camera](./get_camera/)() override | カメラの設定を返します。読み取り専用 [ICamera](../icamera/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ContourColor](./get_contourcolor/)() override | 輪郭の色を返します。読み取り専用 [IColorFormat](../icolorformat/)。 |
| **double** [get_ContourWidth](./get_contourwidth/)() override | 3D 輪郭の幅を返します。読み取り **double**。 |
| **double** [get_Depth](./get_depth/)() override | 3D シェイプの奥行きを返します。読み取り **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ExtrusionColor](./get_extrusioncolor/)() override | 押し出しの色を返します。読み取り専用 [IColorFormat](../icolorformat/)。 |
| **double** [get_ExtrusionHeight](./get_extrusionheight/)() override | 押し出し効果の高さを返します。読み取り **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILightRig](../ilightrig/)\> [get_LightRig](./get_lightrig/)() override | 光源のタイプを返します。読み取り専用 [ILightRig](../ilightrig/)。 |
| [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() override | マテリアルのタイプを返します。読み取り [MaterialPresetType](../materialpresettype/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate オブジェクトを返します。読み取り専用 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../ipresentationcomponent/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormatEffectiveData](../ithreedformateffectivedata/)\> [GetEffective](./geteffective/)() override | 継承が適用された有効な 3-D 書式設定データを取得します。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | ハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文によるロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_ContourWidth](./set_contourwidth/)(**double**) override | 3D 輪郭の幅を設定します。書き込み **double**。 |
| void [set_Depth](./set_depth/)(**double**) override | 3D シェイプの奥行きを設定します。書き込み **double**。 |
| void [set_ExtrusionHeight](./set_extrusionheight/)(**double**) override | 押し出し効果の高さを設定します。書き込み **double**。 |
| void [set_Material](./set_material/)([MaterialPresetType](../materialpresettype/)) override | マテリアルのタイプを設定します。書き込み [MaterialPresetType](../materialpresettype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 補足


次の例は PowerPoint [Presentation](../presentation/) に 3D シェイプを追加する方法を示します。 
```cpp
// Create an instance of Presentation class.
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
次の例は PowerPoint [Presentation](../presentation/) の 3D シェイプにグラデーション効果を適用する方法を示します。 
```cpp
// Presentation クラスのインスタンスを作成します。
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// AddAutoShape メソッドを使用してシェイプを追加します。
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 250.0f, 250.0f);

// TextFrame とそのプロパティを定義します。
shape->get_TextFrame()->set_Text(u"3D Gradient");
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(64.0f);

// FillFormat.FillType を FillType.Gradient に設定し、グラデーションのプロパティを定義します。
shape->get_FillFormat()->set_FillType(FillType::Gradient);
shape->get_FillFormat()->get_GradientFormat()->get_GradientStops()->Add(0.0f, System::Drawing::Color::get_Blue());
shape->get_FillFormat()->get_GradientFormat()->get_GradientStops()->Add(100.0f, System::Drawing::Color::get_Orange());

// ThreeDFormat のプロパティを定義します。
auto threeDFormat = shape->get_ThreeDFormat();
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::OrthographicFront);
threeDFormat->get_Camera()->SetRotation(20.0f, 30.0f, 40.0f);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Flat);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->set_Material(MaterialPresetType::Flat);
threeDFormat->set_ExtrusionHeight(100);
threeDFormat->get_ExtrusionColor()->set_Color(System::Drawing::Color::get_Blue());
slide->GetThumbnail(2.0f, 2.0f)->Save(u"sample_3d.png");

// プレゼンテーションファイルを保存します。
pres->Save(u"sandbox_3d.pptx", SaveFormat::Pptx);
```
次の例はテキストに 3D 効果を適用する方法を示します。3D テキストを作成するには、WordArt の変形効果を使用できます。 
```cpp
// Presentation クラスのインスタンスを作成します。
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// AddAutoShape メソッドを使用してシェイプを追加します。
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 250.0f, 250.0f);

// TextFrame とそのプロパティを定義します。
shape->get_TextFrame()->set_Text(u"3D Text");

// FillFormat.FillType を FillType.NoFill に設定します。
shape->get_FillFormat()->set_FillType(FillType::NoFill);
shape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::NoFill);

// TextFrame の Portion を設定し、PortionFormat のプロパティを設定します。
System::SharedPtr<Portion> portion = System::ExplicitCast<Portion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0));
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Pattern);
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->get_ForeColor()->set_Color(System::Drawing::Color::get_DarkOrange());
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->get_BackColor()->set_Color(System::Drawing::Color::get_White());
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->set_PatternStyle(PatternStyle::LargeGrid);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(128.0f);
System::SharedPtr<ITextFrame> textFrame = shape->get_TextFrame();

// "Arch Up" の WordArt 変形効果を設定します。
textFrame->get_TextFrameFormat()->set_Transform(TextShapeType::ArchUp);

// ITextFrame の ThreeDFormat プロパティを定義します。
auto threeDFormat = textFrame->get_TextFrameFormat()->get_ThreeDFormat();
threeDFormat->set_ExtrusionHeight(3.5f);
threeDFormat->set_Depth(3);
threeDFormat->set_Material(MaterialPresetType::Plastic);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Balanced);
threeDFormat->get_LightRig()->SetRotation(0.0f, 0.0f, 40.0f);
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::PerspectiveContrastingRightFacing);
slide->GetThumbnail(2.0f, 2.0f)->Save(u"text3d.png");

// プレゼンテーションファイルを保存します。
pres->Save(u"text3d.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [PVIObject](../pviobject/)
* クラス [IThreeDFormat](../ithreedformat/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)