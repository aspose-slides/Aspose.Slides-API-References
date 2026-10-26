---
title: Matrix
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje 3x3 matici, která definuje transformační operace. Objektů této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání do funkcí jako argument."
type: docs
weight: 118
url: /cs/system.drawing.drawing2d/matrix/
---
## Matrix třída


Reprezentuje 3×3 matici definující transformační operace. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument.

```cpp
class Matrix : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Vytvoří kopii aktuálního objektu. |
| void [Dispose](./dispose/)() | Uvolní všechny prostředky operačního systému získané aktuálním objektem. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Testuje, zda je zadaný objekt [Matrix](./) a je identický s tímto objektem. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Vrací pole obsahující prvky matice v následujícím pořadí: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Určuje, zda je matice reprezentovaná aktuálním objektem jednotkovou maticí. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Určuje, zda je matice reprezentovaná aktuálním objektem invertovatelná. |
| **float** [get_OffsetX](./get_offsetx/)() const | Vrací hodnotu X posunu matice reprezentované aktuálním objektem. |
| **float** [get_OffsetY](./get_offsety/)() const | Vrací hodnotu Y posunu matice reprezentované aktuálním objektem. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování uživatelských objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | Invertuje matici reprezentovanou aktuálním objektem. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání příkazu C# lock(). Volá se přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
|  [Matrix](./matrix/)() | Vytvoří novou instanci třídy [Matrix](./) reprezentující jednotkovou matici. |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Vytvoří novou instanci třídy [Matrix](./) a inicializuje ji zadanými hodnotami. |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Vytvoří novou instanci třídy [Matrix](./) pro geometrickou transformaci definovanou zadaným obdélníkem a polem bodů. |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Vytvoří novou instanci třídy [Matrix](./) pro geometrickou transformaci definovanou zadaným obdélníkem a polem bodů. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování uživatelských typů. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Násobí matici reprezentovanou aktuálním objektem zadanou maticí. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Násobí matici reprezentovanou aktuálním objektem zadanou maticí. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje konstrukci podtříd kopírováním. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje konstrukci podtříd kopírováním. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává reference objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [Reset](./reset/)() | Resetuje matici reprezentovanou aktuálním objektem tak, aby se stala jednotkovou maticí. |
| void [Rotate](./rotate/)(**float**) | Otočí matici reprezentovanou aktuálním objektem po směru hodinových ručiček o zadaný úhel. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Otočí matici reprezentovanou aktuálním objektem po směru hodinových ručiček kolem počátku o zadaný úhel. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Otočí matici reprezentovanou aktuálním objektem po směru hodinových ručiček kolem zadaného bodu o zadaný úhel. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Otočí matici reprezentovanou aktuálním objektem po směru hodinových ručiček kolem zadaného bodu o zadaný úhel. |
| void [Scale](./scale/)(**float**, **float**) | Aplikuje zadaný škálovací vektor na matici reprezentovanou aktuálním objektem. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Aplikuje zadaný škálovací vektor na matici reprezentovanou aktuálním objektem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (místo sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Shear](./shear/)(**float**, **float**) | Aplikuje zadaný smykový vektor na matici reprezentovanou aktuálním objektem. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Aplikuje zadaný smykový vektor na matici reprezentovanou aktuálním objektem. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod uživatelských objektů na řetězec. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Aplikuje geometrickou transformaci definovanou maticí reprezentovanou aktuálním objektem na zadané body. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Aplikuje geometrickou transformaci definovanou maticí reprezentovanou aktuálním objektem na zadané body. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Aplikuje geometrickou transformaci definovanou maticí reprezentovanou aktuálním objektem na zadané body. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Aplikuje geometrickou transformaci definovanou maticí reprezentovanou aktuálním objektem na zadané body. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Aplikuje pouze škálovací a rotační komponenty matice reprezentované aktuálním objektem na zadané body. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Aplikuje pouze škálovací a rotační komponenty matice reprezentované aktuálním objektem na zadané body. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Aplikuje pouze škálovací a rotační komponenty matice reprezentované aktuálním objektem na zadané body. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Aplikuje pouze škálovací a rotační komponenty matice reprezentované aktuálním objektem na zadané body. |
| void [Translate](./translate/)(**float**, **float**) | Aplikuje zadaný translační vektor na matici reprezentovanou aktuálním objektem. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Aplikuje zadaný translační vektor na matici reprezentovanou aktuálním objektem. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení příkazu C# lock(). Volá se přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Násobí každý vektor v poli maticí reprezentovanou aktuálním objektem. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Násobí každý vektor v poli maticí reprezentovanou aktuálním objektem. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Matrix](./~matrix/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Drawing::Drawing2D](../)
* Knihovna [Aspose.Slides](../../)