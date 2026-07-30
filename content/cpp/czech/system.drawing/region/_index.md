---
title: Region
second_title: Aspose.Slides pro C++ reference API
description: "Představuje vnitřek grafického tvaru. Instance této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám během běhu a/nebo k porušením aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a tento ukazatel používejte k předávání jako argument funkcí."
type: docs
weight: 261
url: /cs/system.drawing/region/
---
## třída Region

Představuje vnitřek grafického tvaru. Instance této třídy by měly být alokovány jen pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo k porušením aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a tento ukazatel používejte k předávání jako argument funkcí.

```cpp
class Region : public System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Vrací kopii aktuálního objektu. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Nahrazuje oblast reprezentovanou aktuálním objektem částí oblasti definované zadaným obdélníkem, která se s touto oblastí nepřekrývá. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Nahrazuje oblast reprezentovanou aktuálním objektem částí oblasti definované zadaným obdélníkem, která se s touto oblastí nepřekrývá. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Nahrazuje oblast reprezentovanou aktuálním objektem částí oblasti definované zadanou cestou, která se s touto oblastí nepřekrývá. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Nahrazuje oblast reprezentovanou aktuálním objektem částí specifikované oblasti, která se s touto oblastí nepřekrývá. |
| void [Dispose](./dispose/)() | Uvolňuje všechny prostředky operačního systému získané aktuálním objektem. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Určuje, zda je zadaná oblast identická s oblastí reprezentovanou aktuálním objektem na specifikovaném kreslicím povrchu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem vyloučení oblasti definované zadaným obdélníkem z ní. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem vyloučení oblasti definované zadaným obdélníkem z ní. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem vyloučení oblasti definované zadanou cestou z ní. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem vyloučení zadané oblasti z ní. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro vnitřní účely. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Získá strukturu [RectangleF](../rectanglef/), která představuje obdélník ohraničující tento [Region](./) na kreslicím povrchu objektu [Graphics](../graphics/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Vrací objekt RegionData obsahující data definující oblast reprezentovanou aktuálním objektem. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Vrací pole struktur [RectangleF](../rectanglef/), které aproximují tento [Region](./) po aplikaci zadané maticové transformace. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem průniku této oblasti a oblasti definované zadaným obdélníkem. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem průniku této oblasti a oblasti definované zadaným obdélníkem. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem průniku této oblasti a oblasti definované zadanou cestou. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem průniku této oblasti a zadané oblasti. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Určuje, zda má oblast reprezentovaná aktuálním objektem prázdný vnitřek na specifikovaném kreslicím povrchu. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Určuje, zda má oblast reprezentovaná aktuálním objektem nekonečný vnitřek na specifikovaném kreslicím povrchu. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Určuje, zda je zadaný bod obsažen v oblasti reprezentované aktuálním objektem. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Určuje, zda je zadaný bod obsažen v oblasti reprezentované aktuálním objektem. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Určuje, zda je jakákoli část zadaného obdélníku obsažena v oblasti reprezentované aktuálním objektem. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Určuje, zda je jakákoli část zadaného obdélníku obsažena v oblasti reprezentované aktuálním objektem. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Určuje, zda je zadaný bod obsažen v oblasti reprezentované aktuálním objektem pomocí specifikované grafiky. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Určuje, zda je zadaný bod obsažen v oblasti reprezentované aktuálním objektem pomocí specifikované grafiky. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Určuje, zda je jakákoli část zadaného obdélníku obsažena v oblasti reprezentované aktuálním objektem pomocí specifikované grafiky. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Určuje, zda je jakákoli část zadaného obdélníku obsažena v oblasti reprezentované aktuálním objektem pomocí specifikované grafiky. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Určuje, zda je zadaný bod obsažen v oblasti reprezentované aktuálním objektem. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Určuje, zda je zadaný bod obsažen v oblasti reprezentované aktuálním objektem pomocí specifikované grafiky. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte hlídací objekt [LockContext](../../system/lockcontext/). |
| void [MakeEmpty](./makeempty/)() | Inicializuje aktuální objekt na prázdný vnitřek. |
| void [MakeInfinite](./makeinfinite/)() | Inicializuje tento objekt regionu na nekonečný vnitřek. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje veškeré vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
|  [Region](./region/)() | Vytvoří novou instanci třídy [Region](./). |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Vytvoří novou instanci třídy [Region](./), která představuje oblast definovanou zadaným obdélníkem. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | Vytvoří novou instanci třídy [Region](./), která představuje oblast definovanou zadaným obdélníkem. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Vytvoří novou instanci třídy [Region](./), která představuje oblast definovanou zadanou cestou. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Vytvoří novou instanci třídy [Region](./), která představuje oblast definovanou zadaným objektem RegionData. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na weak ukazatel (namísto shared). Umožňuje přepínání ukazatelů v kontejnerech do režimu weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Transformuje tuto oblast podle zadané matice. |
| void [Transform](./transform/)(const SkMatrix\&) | Transformuje tuto oblast podle zadané matice. |
| void [Translate](./translate/)(int, int) | Posune souřadnice oblasti o zadanou hodnotu. |
| void [Translate](./translate/)(**float**, **float**) | Posune souřadnice oblasti o zadanou hodnotu. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem operace sjednocení této oblasti a oblasti definované zadaným obdélníkem. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem operace sjednocení této oblasti a oblasti definované zadaným obdélníkem. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem operace sjednocení této oblasti a oblasti definované zadanou cestou. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem operace sjednocení této oblasti a zadané oblasti. |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí C# lock(). Zavolejte přímo nebo použijte hlídací objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje weak čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje weak čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Nahrazuje oblast reprezentovanou aktuálním objektem částmi této oblasti a oblasti definované zadaným obdélníkem, které se nepřekrývají. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Nahrazuje oblast reprezentovanou aktuálním objektem částmi této oblasti a oblasti definované zadaným obdélníkem, které se nepřekrývají. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Nahrazuje oblast reprezentovanou aktuálním objektem částmi této oblasti a oblasti definované zadanou cestou, které se nepřekrývají. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Nahrazuje oblast reprezentovanou aktuálním objektem částmi této oblasti a zadané oblasti, které se nepřekrývají. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
| virtual  [~Region](./~region/)() | Destruktor. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Drawing](../)
* Knihovna [Aspose.Slides](../../)