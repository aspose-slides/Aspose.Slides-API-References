---
title: IModernComment
second_title: Aspose.Slides for C++ API-referencia
description: Egy dián lévő megjegyzést képvisel.
type: docs
weight: 2965
url: /hu/aspose.slides/imoderncomment/
---
## IModernComment osztály

Egy dián lévő megjegyzést képvisel.

```cpp
class IModernComment : public virtual Aspose::Slides::IComment
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szémantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../icomment/get_author/)() | Visszaadja a megjegyzés szerzőjét. Csak olvasható [ICommentAuthor](../icommentauthor/). |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](../icomment/get_createdtime/)() | Visszaadja a megjegyzés létrehozásának időpontját. Ennek a tulajdonságnak a [DateTime::MinValue](../../system/datetime/minvalue/) értékre állítása azt jelenti, hogy nincs megjegyzésidő beállítva. Olvasható [System::DateTime](../../system/datetime/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../icomment/get_parentcomment/)() | Megkapja a szülő megjegyzést. Olvasható [IComment](../icomment/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../icomment/get_position/)() | Visszaadja a megjegyzés helyzetét a dián. Olvasható [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() | Visszaadja a megjegyzéshez kapcsolódó alakzatot. Csak olvasható [IShape](../ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../icomment/get_slide/)() | Visszaadja a megjegyzés szülő diáját. Csak olvasható [ISlide](../islide/). |
| virtual [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() | Visszaadja a megjegyzés állapotát. Olvasható [ModernCommentStatus](../moderncommentstatus/). |
| virtual [System::String](../../system/string/) [get_Text](../icomment/get_text/)() | Visszaadja a dia megjegyzésének egyszerű szövegét. Olvasható [System::String](../../system/string/). |
| virtual **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() | Visszaadja a szövegválasztás hosszát a szövegdobozban, ha a megjegyzés a [AutoShape](../autoshape/)-hoz kapcsolódik. Olvasható **int32_t**. |
| virtual **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() | Visszaadja a szövegválasztás kezdőpozícióját a szövegdobozban, ha a megjegyzés a [AutoShape](../autoshape/)-hez kapcsolódik. Olvasható **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektummal kapcsolatos referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolás konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolás konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint összehasonlítja az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális verziója string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális verziója stringek esetén. |
| virtual void [Remove](../icomment/remove/)() | Eltávolítja a megjegyzést és annak összes válaszát a szülő gyűjteményből. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_CreatedTime](../icomment/set_createdtime/)([System::DateTime](../../system/datetime/)) | Beállítja a megjegyzés létrehozásának időpontját. Ennek a tulajdonságnak a [DateTime::MinValue](../../system/datetime/minvalue/) értékre állítása azt jelenti, hogy nincs megjegyzésidő beállítva. Írható [System::DateTime](../../system/datetime/). |
| virtual void [set_ParentComment](../icomment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) | Beállítja a szülő megjegyzést. Írható [IComment](../icomment/). |
| virtual void [set_Position](../icomment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Beállítja a megjegyzés helyzetét a dián. Írható [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) | Beállítja a megjegyzés állapotát. Írható [ModernCommentStatus](../moderncommentstatus/). |
| virtual void [set_Text](../icomment/set_text/)([System::String](../../system/string/)) | Beállítja a dia megjegyzésének egyszerű szövegét. Írható [System::String](../../system/string/). |
| virtual void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) | Beállítja a szövegválasztás hosszát a szövegdobozban, ha a megjegyzés a [AutoShape](../autoshape/)-hez kapcsolódik. Írható **int32_t**. |
| virtual void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) | Beállítja a szövegválasztás kezdőpozícióját a szövegdobozban, ha a megjegyzés a [AutoShape](../autoshape/)-hez kapcsolódik. Írható **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Állítsa be a n-edik sablonparamétert gyenge mutatóra (nem megosztott). Lehetővé teszi a konténerekben a mutatók gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## Lásd még

* Osztály [IComment](../icomment/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)