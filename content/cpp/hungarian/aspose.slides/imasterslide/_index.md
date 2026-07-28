---
title: IMasterSlide
second_title: Aspose.Slides C++ API referencia
description: Egy prezentációban a mesterdia (master slide) képviselője.
type: docs
weight: 2926
url: /hu/aspose.slides/imasterslide/
---
## IMasterSlide osztály

Egy prezentációban a mesterdia (master slide) képviselője.

```cpp
class IMasterSlide : public virtual Aspose::Slides::IBaseSlide,
                     public Aspose::Slides::Theme::IMasterThemeable
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](./)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) | Létrehoz egy új mesterdiát a jelenlegi alapján, alkalmaz egy külső témát, és a létrehozott mesterdiát az összes függő diára alkalmazza. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | Visszaad egy hatékony témát ehhez a témázható objektumhoz. |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | Meghatározza, hogy a két [IBaseSlide](../ibaseslide/) példány egyenlő-e. A visszatérési érték a dia struktúrája és a statikus tartalom alapján kerül kiszámításra. Két dia akkor egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmat, például a jelenlegi dátumértéket a Date [Placeholder](../placeholder/)-ben. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | Megkeresi a megadott alternatív szöveggel rendelkező alakzat első előfordulását. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | Visszaadja a dia hátterét. Csak olvasható [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() | Visszaadja a törzsszöveg stílusát. Csak olvasható [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | Visszaadja a megadott indexnél lévő ActiveX vezérlőt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | Visszaadja egy dia ActiveX vezérlők gyűjteményét. Csak olvasható [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | Visszaadja a dia egyedi adatait. Csak olvasható [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | Visszaadja a mesterdia rajzolási segédvonalainak gyűjteményét. Csak olvasható [IDrawingGuidesCollection](../idrawingguidescollection/) |
| virtual **bool** [get_HasDependingSlides](./get_hasdependingslides/)() | Igaz értéket ad vissza, ha létezik legalább egy dia, amely ettől a mesterdiától függ. Csak olvasható **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | Visszaadja a mesterdia fejléc/lábléc kezelőjét. Csak olvasható [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. Csak olvasható [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) | Visszaadja a gyerek elrendezés-diat a megadott indexnél ehhez a mesterdiához. Csak olvasható [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() | Visszaadja a gyerek elrendezés-diák gyűjteményét ehhez a mesterdiához. Csak olvasható [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/). |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | Visszaadja egy dia nevét. Olvas [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() | Visszaadja egy másik szöveg stílusát. Csak olvasható [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Visszaadja a prezentációt. Csak olvasható [IPresentation](../ipresentation/). |
| virtual **bool** [get_Preserve](./get_preserve/)() | Meghatározza, hogy a megfelelő mester törlésre kerül-e, amikor az összes, a mester után következő dia törlésre kerül. Megjegyzés: [Aspose.Slides](../) soha nem távolít el önmagában semmilyen felhasználatlan mestert; a felhasználatlan mesterek tényleges eltávolításához hívja meg a [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/) metódust. Olvas **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | Visszaadja az alakzatot a megadott indexnél. Csak olvasható [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | Visszaadja egy dia alakzatait. Csak olvasható [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | Megadja, hogy a mesterdia alakzatai megjelenjen-e a diáken vagy sem. Magára a mesterdiára ez a tulajdonság mindig **false** értéket ad vissza. Olvas **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Visszaadja az alap diát. Csak olvasható [IBaseSlide](../ibaseslide/). |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | Visszaadja egy dia azonosítóját. Csak olvasható **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | Visszaadja a TransitionEx objektumot, amely információt tartalmaz arról, hogyan halad előre a megadott dia egy diavetítés során. Csak olvasható [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](../../aspose.slides.theme/imasterthemeable/get_thememanager/)() | Visszaadja a mester téma kezelőt. Csak olvasható [IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | Visszaadja az animáció idővonal objektumát. Csak olvasható [IAnimationTimeLine](../ianimationtimeline/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() | Visszaadja egy címszöveg stílusát. Csak olvasható [ITextStyle](../itextstyle/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() | Visszaad egy tömböt az összes diával, amelyek ettől a mesterdiától függenek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | Összefűzi az azonos formázású futamokat az összes bekezdésben az összes elfogadható alakzatban. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() állítás zárolását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-el. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | Beállítja egy dia nevét. Írás [System::String](../../system/string/). |
| virtual void [set_Preserve](./set_preserve/)(**bool**) | Meghatározza, hogy a megfelelő mester törlésre kerül-e, amikor az összes, a mester után következő dia törlésre kerül. Megjegyzés: [Aspose.Slides](../) soha nem távolít el önmagában semmilyen felhasználatlan mestert; a felhasználatlan mesterek tényleges eltávolításához hívja meg a [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/). Írás **bool**. |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | Megadja, hogy a mesterdia alakzatai megjelenjen-e a diáken vagy sem. A mesterdia esetében ez a tulajdonság mindig **false** értéket ad vissza. Írás **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (a megosztott helyett) állítja be. Lehetővé teszi a mutatók átállítását a gyengére a konténerekben. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() állítás feloldását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámot. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámot. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IBaseSlide](../ibaseslide/)
* Osztály [IMasterThemeable](../../aspose.slides.theme/imasterthemeable/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)