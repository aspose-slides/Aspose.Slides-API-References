---
title: ModernComment
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje komentář na snímku.
type: docs
weight: 4512
url: /cs/aspose.slides/moderncomment/
---
## ModernComment třída

Represents a comment on a slide.

```cpp
class ModernComment : public Aspose::Slides::Comment,
                      public Aspose::Slides::IModernComment
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typů hodnot ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání floating point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání floating point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../comment/get_author/)() override | Vrací autora komentáře. Pouze pro čtení [ICommentAuthor](../icommentauthor/). |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](../comment/get_createdtime/)() override | Vrací čas vytvoření komentáře. Nastavením této vlastnosti na [DateTime::MinValue](../../system/datetime/minvalue/) znamená, že čas komentáře není nastaven. Pouze čtení [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../comment/get_parentcomment/)() override | Získá nadřazený komentář. Pouze čtení [IComment](../icomment/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../comment/get_position/)() override | Vrací polohu komentáře na snímku. Pouze čtení [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() override | Vrací tvar spojený s komentářem. Pouze pro čtení [IShape](../ishape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../comment/get_slide/)() override | Vrací nadřazený snímek komentáře. Pouze pro čtení [ISlide](../islide/). |
| [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() override | Získá stav komentáře. Pouze čtení [ModernCommentStatus](../moderncommentstatus/). |
| [System::String](../../system/string/) [get_Text](../comment/get_text/)() override | Vrací prostý text komentáře na snímku. Pouze čtení [System::String](../../system/string/). |
| **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() override | Získá délku výběru textu v textovém rámci, pokud je komentář spojen s [AutoShape](../autoshape/). Pouze **int32_t**. |
| **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() override | Získá počáteční pozici výběru textu v textovém rámci, pokud je komentář spojen s [AutoShape](../autoshape/). Pouze **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování uživatelských objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| void [Remove](../comment/remove/)() override | Odstraní komentář a všechny jeho odpovědi z nadřazené kolekce. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [set_CreatedTime](../comment/set_createdtime/)([System::DateTime](../../system/datetime/)) override | Nastaví čas vytvoření komentáře. Nastavením této vlastnosti na [DateTime::MinValue](../../system/datetime/minvalue/) znamená, že čas komentáře není nastaven. Zápis [System::DateTime](../../system/datetime/). |
| void [set_ParentComment](../comment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) override | Nastaví nadřazený komentář. Zápis [IComment](../icomment/). |
| void [set_Position](../comment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Nastaví polohu komentáře na snímku. Zápis [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) override | Nastaví stav komentáře. Zápis [ModernCommentStatus](../moderncommentstatus/). |
| void [set_Text](../comment/set_text/)([System::String](../../system/string/)) override | Nastaví prostý text komentáře na snímku. Zápis [System::String](../../system/string/). |
| void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) override | Nastaví délku výběru textu v textovém rámci, pokud je komentář spojen s [AutoShape](../autoshape/). Zápis **int32_t**. |
| void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) override | Nastaví počáteční pozici výběru textu v textovém rámci, pokud je komentář spojen s [AutoShape](../autoshape/). Zápis **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n'tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převádět uživatelské objekty na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolní všechny interní datové struktury. |

## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [Comment](../comment/)
* Třída [IModernComment](../imoderncomment/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)