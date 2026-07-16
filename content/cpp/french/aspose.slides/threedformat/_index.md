---
title: ThreeDFormat
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente les propriétés 3-D.
type: docs
weight: 5513
url: /fr/aspose.slides/threedformat/
---
## Classe ThreeDFormat

Représente les propriétés 3-D.

```cpp
class ThreeDFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IThreeDFormat
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compare avec l'objet spécifié. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare des objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare des objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelBottom](./get_bevelbottom/)() override | Renvoie le type d'un chanfrein 3D inférieur. Lecture seule [IShapeBevel](../ishapebevel/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelTop](./get_beveltop/)() override | Renvoie le type d'un chanfrein 3D supérieur. Lecture seule [IShapeBevel](../ishapebevel/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICamera](../icamera/)\> [get_Camera](./get_camera/)() override | Renvoie les paramètres d'une caméra. Lecture seule [ICamera](../icamera/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ContourColor](./get_contourcolor/)() override | Renvoie la couleur d'un contour. Lecture seule [IColorFormat](../icolorformat/). |
| **double** [get_ContourWidth](./get_contourwidth/)() override | Renvoie la largeur d'un contour 3D. Lecture **double**. |
| **double** [get_Depth](./get_depth/)() override | Renvoie la profondeur d'une forme 3D. Lecture **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ExtrusionColor](./get_extrusioncolor/)() override | Renvoie la couleur d'une extrusion. Lecture seule [IColorFormat](../icolorformat/). |
| **double** [get_ExtrusionHeight](./get_extrusionheight/)() override | Renvoie la hauteur d'un effet d'extrusion. Lecture **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILightRig](../ilightrig/)\> [get_LightRig](./get_lightrig/)() override | Renvoie le type d'une lumière. Lecture seule [ILightRig](../ilightrig/). |
| [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() override | Renvoie le type d'un matériau. Lecture [MaterialPresetType](../materialpresettype/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Renvoie l'objet Parent_Immediate. Lecture seule [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Renvoie le parent [IPresentationComponent](../ipresentationcomponent/). Lecture seule [IPresentationComponent](../ipresentationcomponent/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de référence associée à l'objet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormatEffectiveData](../ithreedformateffectivedata/)\> [GetEffective](./geteffective/)() override | Obtient les données de formatage 3D effectives avec l'héritage appliqué. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Renvoie le code de hachage. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet de cloner des types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_ContourWidth](./set_contourwidth/)(**double**) override | Définit la largeur d'un contour 3D. Écriture **double**. |
| void [set_Depth](./set_depth/)(**double**) override | Définit la profondeur d'une forme 3D. Écriture **double**. |
| void [set_ExtrusionHeight](./set_extrusionheight/)(**double**) override | Définit la hauteur d'un effet d'extrusion. Écriture **double**. |
| void [set_Material](./set_material/)([MaterialPresetType](../materialpresettype/)) override | Définit le type d'un matériau. Écriture [MaterialPresetType](../materialpresettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Remarques

L'exemple suivant montre comment ajouter une forme 3D dans PowerPoint [Presentation](../presentation/). 
```cpp
// Créez une instance de la classe Presentation.
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
L'exemple suivant montre comment appliquer un effet de dégradé à une forme 3D dans PowerPoint [Presentation](../presentation/). 
```cpp
// Créez une instance de la classe Presentation.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Add a shape using AddAutoShape method
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 250.0f, 250.0f);

// Define TextFrame and its properties
shape->get_TextFrame()->set_Text(u"3D Gradient");
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(64.0f);

// Configure FillFormat.FillType as FillType.Gradient and define gradient properties
shape->get_FillFormat()->set_FillType(FillType::Gradient);
shape->get_FillFormat()->get_GradientFormat()->get_GradientStops()->Add(0.0f, System::Drawing::Color::get_Blue());
shape->get_FillFormat()->get_GradientFormat()->get_GradientStops()->Add(100.0f, System::Drawing::Color::get_Orange());

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

// Enregistrez le fichier Presentation
pres->Save(u"sandbox_3d.pptx", SaveFormat::Pptx);
```
L'exemple suivant montre comment appliquer un effet 3D sur du texte. Pour créer du texte 3D, il est possible d'utiliser l'effet de transformation WordArt. 
```cpp
// Créez une instance de la classe Presentation.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Ajoutez une forme en utilisant la méthode AddAutoShape method
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 250.0f, 250.0f);

// Définissez le TextFrame et ses propriétés
shape->get_TextFrame()->set_Text(u"3D Text");

// Configurez FillFormat.FillType comme FillType.NoFill
shape->get_FillFormat()->set_FillType(FillType::NoFill);
shape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::NoFill);

// Configurez la portion du TextFrame et ses propriétés de PortionFormat
System::SharedPtr<Portion> portion = System::ExplicitCast<Portion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0));
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Pattern);
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->get_ForeColor()->set_Color(System::Drawing::Color::get_DarkOrange());
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->get_BackColor()->set_Color(System::Drawing::Color::get_White());
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->set_PatternStyle(PatternStyle::LargeGrid);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(128.0f);
System::SharedPtr<ITextFrame> textFrame = shape->get_TextFrame();

// Configurez l'effet de transformation WordArt "Arch Up"
textFrame->get_TextFrameFormat()->set_Transform(TextShapeType::ArchUp);

// Définissez les propriétés ThreeDFormat de ITextFrame
auto threeDFormat = textFrame->get_TextFrameFormat()->get_ThreeDFormat();
threeDFormat->set_ExtrusionHeight(3.5f);
threeDFormat->set_Depth(3);
threeDFormat->set_Material(MaterialPresetType::Plastic);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Balanced);
threeDFormat->get_LightRig()->SetRotation(0.0f, 0.0f, 40.0f);
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::PerspectiveContrastingRightFacing);
slide->GetThumbnail(2.0f, 2.0f)->Save(u"text3d.png");

// Enregistrez le fichier Presentation
pres->Save(u"text3d.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [PVIObject](../pviobject/)
* Classe [IThreeDFormat](../ithreedformat/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)