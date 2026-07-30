---
title: System
second_title: Aspose.Slides pro C++ - referenční API
description: 
type: docs
weight: 274
url: /cs/system/
---
## Třídy

| Class | Description |
| --- | --- |
| [Activator](./activator/) | Obsahuje metody pro vytváření typů objektů. |
| [Array](./array/) | Třída představující datovou strukturu pole. Objektům této třídy by mělo být přidělováno pouze pomocí [System::MakeArray()](./makearray/) a [System::MakeObject()](./makeobject/) funkcí. Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operator new, protože to povede k běhovým chybám a/nebo chybám při aserce. Vždy zabalte tuto třídu do [System::SmartPtr](./smartptr/) ukazatele a použijte tento ukazatel k předání funkcím jako argument. |
| [ArrayBase](./arraybase/) | Fiktivní třída pro [System.Array](./array/) (abstraktní základní třída pro všechna pole) může být doplněna o funkčnost na požádání. |
| [ArraySegment](./arraysegment/) | Představuje segment jednorozměrného pole. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k řízení objektů tohoto typu. |
| [Attribute](./attribute/) | Základní třída pro vlastní atributy. Objektům této třídy by mělo být přidělováno pouze pomocí [System::MakeObject()](./makeobject/) funkce. Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operator new, protože to povede k běhovým chybám a/nebo chybám při aserce. Vždy zabalte tuto třídu do [System::SmartPtr](./smartptr/) ukazatele a použijte tento ukazatel k předání funkcím jako argument. |
| [BitConverter](./bitconverter/) | Obsahuje metody provádějící převody sekvence bajtů na typ hodnoty a naopak. Jedná se o statický typ bez instančních služeb. Neměli byste nikdy vytvářet jeho instance jakýmkoli způsobem. |
| [Boolean](./boolean/) | Třída uchovávající statické členy typu [System.Boolean](./boolean/) .[Net](../system.net/). |
| [BoxedEnum](./boxedenum/) | Představuje zabalenou hodnotu výčtu. Objektům této třídy by mělo být přidělováno pouze pomocí [System::MakeObject()](./makeobject/) funkce. Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operator new, protože to povede k běhovým chybám a/nebo chybám při aserce. Vždy zabalte tuto třídu do [System::SmartPtr](./smartptr/) ukazatele a použijte tento ukazatel k předání funkcím jako argument. |
| [BoxedValue](./boxedvalue/) | Představuje zabalenou hodnotu. Objektům této třídy by mělo být přidělováno pouze pomocí [System::MakeObject()](./makeobject/) funkce. Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operator new, protože to povede k běhovým chybám a/nebo chybám při aserce. Vždy zabalte tuto třídu do [System::SmartPtr](./smartptr/) ukazatele a použijte tento ukazatel k předání funkcím jako argument. |
| [BoxedValue< ValueTuple< Args... > >](./boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/) | Zabalena verze hodnotové n-tice. |
| [BoxedValueBase](./boxedvaluebase/) | Základní třída, která definuje rozhraní a implementuje některé základní metody odvozené třídy představující zabalenou hodnotu. Objektům této třídy by mělo být přidělováno pouze pomocí [System::MakeObject()](./makeobject/) funkce. Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operator new, protože to povede k běhovým chybám a/nebo chybám při aserce. Vždy zabalte tuto třídu do [System::SmartPtr](./smartptr/) ukazatele a použijte tento ukazatel k předání funkcím jako argument. |
| [Buffer](./buffer/) | Obsahuje metody, které manipulují se surovými poli bajtů. Jedná se o statický typ bez instančních služeb. Neměli byste nikdy vytvářet jeho instance jakýmkoli způsobem. |
| [Byte](./byte/) | Obsahuje metody pro práci s neoznačeným 8-bitovým celým číslem. |
| [Char](./char/) | Poskytuje metody pro manipulaci se znaky reprezentovanými jako kódové jednotky UTF-16. Jedná se o statický typ bez instančních služeb. Neměli byste nikdy vytvářet jeho instance jakýmkoli způsobem. |
| [Comparison](./comparison/) | Představuje ukazatel na metodu, která porovnává dva objekty stejného typu. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k řízení objektů tohoto typu. |
| [Console](./console/) | Poskytuje metody pro výstup dat do standardního výstupního proudu. Jedná se o statický typ bez instančních služeb. Neměli byste nikdy vytvářet jeho instance jakýmkoli způsobem. |
| [ConsoleOutput](./consoleoutput/) | Představuje standardní výstupní proud. Objektům této třídy by mělo být přidělováno pouze pomocí [System::MakeObject()](./makeobject/) funkce. Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operator new, protože to povede k běhovým chybám a/nebo chybám při aserce. Vždy zabalte tuto třídu do [System::SmartPtr](./smartptr/) ukazatele a použijte tento ukazatel k předání funkcím jako argument. |
| [DateTime](./datetime/) | Představuje konkrétní datum a čas v časové kontinuu. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k řízení objektů tohoto typu. |
| [DateTimeOffset](./datetimeoffset/) | Obsahuje datum a čas dne vzhledem k koordinovanému světovému času (UTC). Objektům této třídy by mělo být přidělováno pouze pomocí [System::MakeObject()](./makeobject/) funkce. Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operator new, protože to povede k běhovým chybám a/nebo chybám při aserce. Vždy zabalte tuto třídu do [System::SmartPtr](./smartptr/) ukazatele a použijte tento ukazatel k předání funkcím jako argument. |
| [DBNull](./dbnull/) | Představuje neexistující hodnotu. Objektům této třídy by mělo být přidělováno pouze pomocí [System::MakeObject()](./makeobject/) funkce. Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operator new, protože to povede k běhovým chybám a/nebo chybám při aserce. Vždy zabalte tuto třídu do [System::SmartPtr](./smartptr/) ukazatele a použijte tento ukazatel k předání funkcím jako argument. |
| [Decimal](./decimal/) | Představuje desetinné číslo. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k řízení objektů tohoto typu. |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) implementace třídy. Umožňuje deklarovat specializace BoxingValue bez duplikace společného kódu. Objektům této třídy by mělo být přidělováno pouze pomocí [System::MakeObject()](./makeobject/) funkce. Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operator new, protože to povede k běhovým chybám a/nebo chybám při aserce. Vždy zabalte tuto třídu do [System::SmartPtr](./smartptr/) ukazatele a použijte tento ukazatel k předání funkcím jako argument. |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | Představuje ukazatel na funkci, metodu nebo funkcionální objekt. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k řízení objektů tohoto typu. |
| [Details_AggregateException](./details_aggregateexception/) | Představuje výjimku, která obsahuje více vnitřních výjimek. |
| [Details_ApplicationException](./details_applicationexception/) | Základní třída pro třídy představující výjimky aplikace (na rozdíl od systémových). Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu ApplicationException. Nikdy nezabaluujte instance třídy ApplicationException do [System::SmartPtr](./smartptr/). |
| [Details_ArgumentException](./details_argumentexception/) | ArgumentException je vyvolána, když je předán metodě neplatný argument. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu ArgumentException. Nikdy nezabaluujte instance třídy ArgumentException do [System::SmartPtr](./smartptr/). |
| [Details_ArgumentNullException](./details_argumentnullexception/) |  |
| [Details_ArgumentOutOfRangeException](./details_argumentoutofrangeexception/) | ArgumentOutOfRangeException je vyvolána, když je metodě předán argument mimo očekávaný rozsah hodnot pro tento argument. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu ArgumentOutOfRangeException. Nikdy nezabaluujte instance třídy ArgumentOutOfRangeException do [System::SmartPtr](./smartptr/). |
| [Details_ArithmeticException](./details_arithmeticexception/) | ArithmeticException je vyvolána, když dojde k chybě během provádění aritmetických operací či konverze při přetypování. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu ArithmeticException. Nikdy nezabaluujte instance třídy ArithmeticException do [System::SmartPtr](./smartptr/). |
| [Details_BadImageFormatException](./details_badimageformatexception/) | Výjimka, která je vyvolána, když je souborový obraz dynamické knihovny (DLL) nebo spustitelného programu neplatný. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu BadImageFormatException. Nikdy nezabaluujte instance třídy BadImageFormatException do [System::SmartPtr](./smartptr/). |
| [Details_DataMisalignedException](./details_datamisalignedexception/) |  |
| [Details_DivideByZeroException](./details_dividebyzeroexception/) | DivideByZeroException je vyvolána, když je v aritmetické operaci pokus o dělení nulou. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu DivideByZeroException. Nikdy nezabaluujte instance třídy DivideByZeroException do [System::SmartPtr](./smartptr/). |
| [Details_Exception](./details_exception/) | Představuje výjimku. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu Exception. Nikdy nezabaluujte instance třídy Exception do [System::SmartPtr](./smartptr/). |
| [Details_ExceptionWithErrorCode](./details_exceptionwitherrorcode/) | Šablonová třída pro výjimku s chybovým kódem. |
| [Details_ExceptionWithFilename](./details_exceptionwithfilename/) | Šablonová třída pro výjimku s názvem souboru. |
| [Details_ExecutionEngineException](./details_executionengineexception/) | ExecutionEngineException existuje pouze z důvodů kompatibility. |
| [Details_FormatException](./details_formatexception/) | FormatException je vyvolána, když formát argumentu metody není platný. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu FormatException. Nikdy nezabaluujte instance třídy FormatException do [System::SmartPtr](./smartptr/). |
| [Details_IndexOutOfRangeException](./details_indexoutofrangeexception/) | IndexOutOfRangeException je vyvolána, když je pokus o přístup k prvku kolekce pomocí indexu mimo jeho hranice. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu IndexOutOfRangeException. Nikdy nezabaluujte instance třídy IndexOutOfRangeException do [System::SmartPtr](./smartptr/). |
| [Details_InvalidCastException](./details_invalidcastexception/) | InvalidCastException je vyvolána, když je provedena neplatná operace přetypování nebo neplatná explicitní konverze. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu InvalidCastException. Nikdy nezabaluujte instance třídy InvalidCastException do [System::SmartPtr](./smartptr/). |
| [Details_InvalidOperationException](./details_invalidoperationexception/) | Výjimka, která je vyvolána, když je metoda volána na objektu, který je ve stavu nekompatibilním s tímto voláním. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu InvalidOperationException. Nikdy nezabaluujte instance třídy InvalidOperationException do [System::SmartPtr](./smartptr/). |
| [Details_InvalidProgramException](./details_invalidprogramexception/) | InvalidProgramException existuje pouze z důvodů kompatibility. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu InvalidProgramException. Nikdy nezabaluujte instance třídy InvalidProgramException do [System::SmartPtr](./smartptr/). |
| [Details_InvalidTimeZoneException](./details_invalidtimezoneexception/) | InvalidTimeZoneException je vyvolána, když jsou informace o časové zóně neplatné. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu InvalidTimeZoneException. Nikdy nezabaluujte instance třídy InvalidTimeZoneException do [System::SmartPtr](./smartptr/). |
| [Details_MemberAccessException](./details_memberaccessexception/) | MemberAccessException je vyvolána, když je pokus o přístup k neexistujícímu členovi třídy nebo když není přístup k členu povolen. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu MemberAccessException. Nikdy nezabaluujte instance třídy MemberAccessException do [System::SmartPtr](./smartptr/). |
| [Details_MethodAccessException](./details_methodaccessexception/) | MemberAccessException je vyvolána, když je pokus o přístup k neexistující metodě nebo když není přístup k metodě povolen. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu MethodAccessException. Nikdy nezabaluujte instance třídy MethodAccessException do [System::SmartPtr](./smartptr/). |
| [Details_NotImplementedException](./details_notimplementedexception/) | NotImplementedException je vyvolána, když je volána metoda, která není implementována a slouží jako zástupce. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu NotImplementedException. Nikdy nezabaluujte instance třídy NotImplementedException do [System::SmartPtr](./smartptr/). |
| [Details_NotSupportedException](./details_notsupportedexception/) | NotSupportedException je vyvolána, když je volaná metoda nepodporovaná nebo když operace na proudu není podporována. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu NotSupportedException. Nikdy nezabaluujte instance třídy NotSupportedException do [System::SmartPtr](./smartptr/). |
| [Details_NullReferenceException](./details_nullreferenceexception/) | NullReferenceException je vyvolána, když je pokus o dereferenci nulové reference. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu NullReferenceException. Nikdy nezabaluujte instance třídy NullReferenceException do [System::SmartPtr](./smartptr/). |
| [Details_ObjectDisposedException](./details_objectdisposedexception/) | ObjectDisposedException je vyvolána, když je metoda volána na zrušeném (disposed) objektu. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu ObjectDisposedException. Nikdy nezabaluujte instance třídy ObjectDisposedException do [System::SmartPtr](./smartptr/). |
| [Details_OperationCanceledException](./details_operationcanceledexception/) | OperationCanceledException je vyvolána ve vlákně při zrušení operace, kterou vlákno provádělo. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu OperationCanceledException. Nikdy nezabaluujte instance třídy OperationCanceledException do [System::SmartPtr](./smartptr/). |
| [Details_OutOfMemoryException](./details_outofmemoryexception/) |  |
| [Details_OverflowException](./details_overflowexception/) | OverflowException je vyvolána, když operace způsobí přetečení. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu OverflowException. Nikdy nezabaluujte instance třídy OverflowException do [System::SmartPtr](./smartptr/). |
| [Details_PlatformNotSupportedException](./details_platformnotsupportedexception/) | PlatformNotSupportedException se vyvolá, když funkce neprobíhá na konkrétní platformě. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu PlatformNotSupportedException. Nikdy neobalujte instance třídy PlatformNotSupportedException do [System::SmartPtr](./smartptr/). |
| [Details_RankException](./details_rankexception/) | RankException se vyvolá, když je metodě předán pole argument s počtem rozměrů odlišným od očekávaného. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu RankException. Nikdy neobalujte instance třídy RankException do [System::SmartPtr](./smartptr/). |
| [Details_StackOverflowException](./details_stackoverflowexception/) | StackOverflowException se vyvolá, když přeteče zásobník vykonávacího vlákna. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu StackOverflowException. Nikdy neobalujte instance třídy StackOverflowException do [System::SmartPtr](./smartptr/). |
| [Details_SystemException](./details_systemexception/) | Základní třída pro třídy, které představují systémové (spíše než aplikační) výjimky. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu SystemException. Nikdy neobalujte instance třídy SystemException do [System::SmartPtr](./smartptr/). |
| [Details_TimeoutException](./details_timeoutexception/) | TimeoutException indikuje, že čas přidělený pro proces nebo operaci vypršel. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu TimeoutException. Nikdy neobalujte instance třídy TimeoutException do [System::SmartPtr](./smartptr/). |
| [Details_TimeZoneNotFoundException](./details_timezonenotfoundexception/) | TimeZoneNotFoundException se vyvolá, když není nalezena informace o časovém pásmu. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu TimeZoneNotFoundException. Nikdy neobalujte instance třídy TimeZoneNotFoundException do [System::SmartPtr](./smartptr/). |
| [Details_TypeInitializationException](./details_typeinitializationexception/) |  |
| [Details_UnauthorizedAccessException](./details_unauthorizedaccessexception/) | UnauthorizedAccessException se vyvolá, když operační systém odmítne přístup kvůli I/O chybě nebo bezpečnostní chybě. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu UnauthorizedAccessException. Nikdy neobalujte instance třídy UnauthorizedAccessException do [System::SmartPtr](./smartptr/). |
| [Details_UriFormatException](./details_uriformatexception/) | UriFormatException se vyvolá, když formát URI není platný. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu UriFormatException. Nikdy neobalujte instance třídy UriFormatException do [System::SmartPtr](./smartptr/). |
| [DynamicWeakPtr](./dynamicweakptr/) | Třída chytrého ukazatele, která sleduje režimy ukazatelů šablonových argumentů uloženého objektu a aktualizuje je po každém přiřazení. Tento typ je ukazatel pro správu odstranění jiného objektu. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo konstantní referencí. |
| [EnumValues](./enumvalues/) | Poskytuje meta informace o konstantách výčtu typu enum **E**. |
| [EnumValuesBase](./enumvaluesbase/) | Základní třída pro třídu, která představuje meta informace typu výčtu. |
| [EventArgs](./eventargs/) | Základní třída pro třídy, které představují kontext předávaný předplatitelům událostí při spuštění události. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel k předání funkcím jako argument. |
| [ExceptionWrapper](./exceptionwrapper/) | Šablona, která představuje obal výjimek odvozených od třídy Exception. |
| [FlagsAttribute](./flagsattribute/) | Indikuje, že výčet může být považován za bitové pole; tj. za množinu. |
| [Func](./func/) | Funkční delegát. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [GC](./gc/) | Představuje emulovanou garbage collection, která funguje spíše jako stub a v podstatě nic nedělá. Jedná se o statický typ bez služeb instance. Neměli byste nikdy vytvářet jeho instance jakýmkoli způsobem. |
| [Guid](./guid/) | Představuje globálně jedinečný identifikátor (GUID). Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [IAsyncResult](./iasyncresult/) | Representuje stav asynchronní operace. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel při předávání funkcím jako argument. |
| [ICloneable](./icloneable/) | Definuje metodu, která umožňuje klonování objektu – vytvoření kopie objektu. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel při předávání funkcím jako argument. |
| [IComparable](./icomparable/) | Definuje metodu, která porovnává dva objekty. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel při předávání funkcím jako argument. |
| [IConvertible](./iconvertible/) | Definuje metody, které převádějí hodnotu implementujícího reference nebo hodnotového typu na typ běhového prostředí Common Language Runtime (CLR), který má ekvivalentní hodnotu. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel při předávání funkcím jako argument. |
| [ICustomFormatter](./icustomformatter/) | Definuje metodu, která provádí vlastní formátování řetězcové reprezentace hodnoty reprezentované daným objektem. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel při předávání funkcím jako argument. |
| [IDisposable](./idisposable/) | Definuje metodu, která uvolňuje zdroje vlastněné aktuálním objektem. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel při předávání funkcím jako argument. |
| [IEquatable](./iequatable/) | Definuje metodu, která určuje rovnost dvou objektů. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel při předávání funkcím jako argument. |
| [IFormatProvider](./iformatprovider/) | Definuje metodu, která poskytuje informace o formátování. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel při předávání funkcím jako argument. |
| [IFormattable](./iformattable/) | Definuje metodu, která formátuje hodnotu aktuálního objektu pomocí zadaného řetězce formátu a poskytovatele formátu. |
| [Index](./index/) | Představuje index do kolekce. Index může být od začátku nebo od konce. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [Int16](./int16/) | Obsahuje metody pro práci s 16bitovým celočíselným typem. |
| [Int32](./int32/) | Obsahuje metody pro práci s 32bitovým celočíselným typem. |
| [Int64](./int64/) | Obsahuje metody pro práci s 64bitovým celočíselným typem. |
| [LockContext](./lockcontext/) | Ochranný objekt implementující C# lock() statement. |
| [MarshalByRefObject](./marshalbyrefobject/) | Poskytuje přístup k objektům napříč hranicemi aplikačních domén v aplikacích s povoleným remote přenosem. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel při předávání funkcím jako argument. |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | Představuje kolekci delegátů. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [Nullable](./nullable/) | Předběžná deklarace. |
| [NullableUtils](./nullableutils/) | Představuje statickou třídu C# [System.Nullable](./nullable/) (bez typových argumentů). Původní název nelze použít kvůli neschopnosti přetížit šablony tříd v C++. Podporuje hodnotový typ, kterému lze přiřadit null. Tuto třídu nelze dědit. |
| [Object](./object/) | Základní třída umožňující používání metod dostupných pro třídu [System.Object](./object/) v C#. Všechny ne-triviální třídy použité v přeloženém prostředí by měly tuto třídu dědit. |
| [ObjectExt](./objectext/) | Poskytuje statické metody, které emulují C# [Object](./object/) metody volané pro ne-Object C++ typy (řetězce, čísla atd.). Jedná se o statický typ bez služeb instance. Neměli byste nikdy vytvářet jeho instance jakýmkoli způsobem. |
| [ObjectType](./objecttype/) | Poskytuje statické metody implementující získávače typů objektů. Jedná se o statický typ bez služeb instance. Neměli byste nikdy vytvářet jeho instance jakýmkoli způsobem. |
| [OperatingSystem](./operatingsystem/) | Představuje konkrétní operační systém a poskytuje o něm informace. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel při předávání funkcím jako argument. |
| [Random](./random/) | Představuje pseudo-náhodný generátor čísel. Objektům této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel při předávání funkcím jako argument. |
| [Range](./range/) | Představuje rozsah se startovacím a koncovým indexem. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [ReadOnlySpan](./readonlyspan/) | Přesměrování pro použití v rámci třídy [Span](./span/). |
| [ScopedCulture](./scopedculture/) | Představuje kulturu používanou v rámci rozsahu. |
| [SmartPtr](./smartptr/) | Třída ukazatele pro zabalení typů alokovaných na haldě. Použijte ji pro správu paměti tříd dědících [Object](./object/). Tento typ ukazatele používá intruzivní semantiku ukazatelů. Počítadlo odkazů je uloženo buď v samotném [Object](./object/), nebo ve struktuře počítadla, která je úzce svázána s instancí [Object](./object/). V každém případě všechny instance [SmartPtr](./smartptr/) tvoří jediné vlastnické skupiny bez ohledu na to, jak byly vytvořeny, což se liší od chování třídy std::shared_ptr. Převod surového ukazatele na [SmartPtr](./smartptr/) je bezpečný, pokud existují další instance [SmartPtr](./smartptr/) držící sdílené odkazy na stejný objekt. Instance třídy [SmartPtr](./smartptr/) může být ve dvou stavech: sdílený ukazatel a slabý ukazatel. Aby objekt zůstal živý, měl by být počet sdílených odkazů na něj kladný. Jak slabé, tak sdílené ukazatele mohou být použity k přístupu k ukazovanému objektu (volání metod, čtení nebo zápis polí atd.), ale slabé ukazatele se neúčastní počítání referencí sdílených ukazatelů. [Object](./object/) je mazán, když je zničen poslední 'shared' [SmartPtr](./smartptr/) ukazatel na něj. Proto se ujistěte, že se to nestane, když neexistují žádné další sdílené [SmartPtr](./smartptr/) ukazatele na objekt, např. během konstrukce nebo destrukce objektu. Použijte objekty System::Object::ThisProtector (v kódu C++) nebo atributy CppCTORSelfReference či CppSelfReference (v překládáném kódu C#) k nápravě tohoto problému. Podobně zajistěte rozbití cyklických odkazů pomocí třídy ukazatele [System::WeakPtr](./weakptr/) nebo režimu ukazatele [System::SmartPtrMode::Weak](./smartptrmode/) (v kódu C++) nebo atributu CppWeakPtr (v překládáném kódu C#). Pokud dva nebo více objektů odkazují na sebe pomocí 'shared' ukazatelů, nikdy nebudou smazány. Pokud má být typ ukazatele (slabý nebo sdílený) za běhu změněn, použijte metodu [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) nebo třídu [System::DynamicWeakPtr](./dynamicweakptr/). Třída [SmartPtr](./smartptr/) neobsahuje žádné virtuální metody. Měli byste z ní dědit pouze pokud vytváříte vlastní strategii správy paměti. Tento typ je ukazatel pro správu mazání jiného objektu. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo jako const reference. |
| [SmartPtrInfo](./smartptrinfo/) | Služební třída pro testování a úpravu obsahu [SmartPtr](./smartptr/) bez znalosti konečného typu. Používá se pro odstraňování nevyužité paměti a detekci cyklických odkazů atd. Považujte ji za 'ukazatel na ukazatel'. Nemůžeme použít základní typ [SmartPtr](./smartptr/), protože žádný nemá; místo toho používáme tuto 'info' třídu. |
| [Span](./span/) | Representuje souvislý region libovolné paměti podobný std::span z C++20. |
| [String](./string/) | Třída [String](./string/) používaná napříč knihovnou. Je náhradou za C# [System.String](./string/) při překladu kódu. Z optimalizačních důvodů není považována za podtřídu [Object](./object/). Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [StringComparer](./stringcomparer/) | Srovnává řetězce pomocí různých režimů porovnání. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [StringHashCompiletime](./stringhashcompiletime/) | Pomocná třída, která generuje hash hodnotu z c-stringu. |
| [TimeSpan](./timespan/) | Representuje časový interval. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [TimeZone](./timezone/) | Representuje časové pásmo. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [TimeZoneInfo](./timezoneinfo/) | Representuje informaci popisující konkrétní časové pásmo. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [Tuple](./tuple/) | Třída představující datovou strukturu n-tice. Maximální počet položek je 8. |
| [TupleFactory](./tuplefactory/) | Poskytuje statické metody pro vytváření objektů n-tic. |
| [TypeInfo](./typeinfo/) | Representuje konkrétní typ a poskytuje o něm informace. |
| [Uri](./uri/) | Jednotný identifikátor zdroje. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [UriBuilder](./uribuilder/) | Poskytuje metody pro vytváření a úpravu univerzálních identifikátorů zdrojů (URI). Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [UriParser](./uriparser/) | Používá se k parsování nového schématu URI. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](./makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](./smartptr/) a použijte tento ukazatel k předání jako argument funkcím. |
| [UriShim](./urishim/) | Servisní třída. |
| [ValueTuple](./valuetuple/) | Třída představující datovou strukturu [ValueTuple](./valuetuple/). |
| [ValueType](./valuetype/) | Základní třída pro hodnotové typy s [Object](./object/) dědičností, která je zkrácena z výkonnostních důvodů. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [Version](./version/) | Representuje číslo verze. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | Podtřída [System::SmartPtr](./smartptr/), která se při konstrukci nastaví do slabého režimu. Všimněte si, že tato třída nezaručuje, že její instance bude vždy zůstávat ve slabém režimu, protože [set_Mode()](./smartptr/set_mode/) je stále přístupný. Tento typ je ukazatel pro správu mazání jiného objektu. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo jako const reference. |
| [WeakReference< T >](./weakreference_tmpl_t__end_tmpl/) | Representuje slabý odkaz, který odkazuje na objekt, ale přitom umožňuje, aby byl objekt smazán. |
| [WeakReference<>](./weakreference_tmpl_end_tmpl/) | Representuje slabý odkaz, který odkazuje na objekt, ale přitom umožňuje, aby byl objekt smazán. |

## Struktury

| Struktura | Popis |
| --- | --- |
| [CastResult](./castresult/) | Magie šablon pro odvození výsledků přetypování. |
| [CollectionAssertHelper](./collectionasserthelper/) | Pomocné API pro operace související s kolekcemi. |
| [Convert](./convert/) | Struktura, která obsahuje metody provádějící konverzi hodnot jednoho typu na hodnoty jiného typu. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [Double](./double/) | Obsahuje metody pro práci s dvojitou přesností floating-point číslem. |
| [Enum](./enum/) | Poskytuje metody, které provádějí některé operace na hodnotách výčtového typu. Jedná se o statický typ bez instance služeb. Nikdy byste neměli vytvářet jeho instance jakýmkoli způsobem. |
| [EnumGetNameHelper](./enumgetnamehelper/) | Pomocná třída, která poskytuje funkci získání názvu enum konstanty. |
| [EnumParseHelper](./enumparsehelper/) | Pomocná třída, která poskytuje funkci převodu řetězcové reprezentace enum konstanty na ekvivalentní enum hodnotu. |
| [Environment](./environment/) | [Environment](./environment/) služby. Jedná se o statický typ bez instance služeb. Nikdy byste neměli vytvářet jeho instance jakýmkoli způsobem. |
| [HolderInitializer](./holderinitializer/) | Třída slouží k získání perzistentního odkazu na instanci objektu, ať už jde o lvalue nebo rvalue. Pro získání takového odkazu použijte metodu 'HoldIfTemporary', která má tři přetížení. Dvě z nich přijímají rvalue jako parametr a vrací na něj odkaz. Třetí, naopak, přijímá lvalue jako parametr, vytvoří kopii ukazatele a vrátí odkaz na tuto kopii. Třída také obsahuje metodu 'Hold' pro neomezené udržení předané hodnoty (používá se k kopírování hodnot lokálních proměnných na zásobníku nebo jejich podřízených odkazů). |
| [HolderInitializer< T, false >](./holderinitializer_tmpl_t__false__end_tmpl/) | Specializace [HolderInitializer](./holderinitializer/) pro případ, kdy T je typ hodnoty. Kontext použití umožňuje vrátit odkaz na dočasné objekty, protože je zaručeno, že instance bude volajícím zkopírována. Tato specializace je tedy používána jen jako zástupce a neprovádí žádnou akci. |
| [IsBoxable](./isboxable/) | Predikát šablony, který kontroluje, zda je podporováno boxování zadaného typu. |
| [IsExceptionWrapper](./isexceptionwrapper/) | Predikát šablony, který určuje, zda je zadaný typ třídou Exception nebo jejím potomkem. |
| [IsNullable](./isnullable/) | Predikát šablony, který určuje, zda je jeho šablonový argument T v [Nullable](./nullable/) nebo v jeho podtřídě. |
| [IsSmartPtr](./issmartptr/) | Trait třída pro kontrolu, zda je typ specializací třídy [SmartPtr](./smartptr/). |
| [IsStringByteSequence](./isstringbytesequence/) | Magie šablon pro kontrolu, zda je typ sekvencí znakových řetězců. |
| [IsStringLiteral](./isstringliteral/) | Magie šablon pro kontrolu, zda je typ řetězcovým literálem. |
| [IsStringPointer](./isstringpointer/) | Magie šablon pro kontrolu, zda je typ ukazatelem na znakový řetězec. |
| [IsWeakPtr](./isweakptr/) | Trait třída pro kontrolu, zda je konkrétní třída specializací [System::WeakPtr](./weakptr/). Nekontroluje, zda je instance skutečně ve slabém režimu. |
| [MakeConstRef](./makeconstref/) | Trait pro vytvoření generického typu "const reference", pokud je to [String](./string/) nebo typ SmartPtr<>. |
| [Math](./math/) | Obsahuje matematické funkce. Jedná se o statický typ bez instance služeb. Nikdy byste neměli vytvářet jeho instance jakýmkoli způsobem. |
| [MathF](./mathf/) | Obsahuje matematické funkce pro hodnoty s jednoduchou přesností floating-point. Jedná se o statický typ bez instance služeb. Nikdy byste neměli vytvářet jeho instance jakýmkoli způsobem. |
| [MethodArgumentTuple< R(*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | Definuje n-tici pro uložení argumentů metody. |
| [MethodArgumentTuple< R(C::*)(Args...) const >](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/) | Definuje n-tici pro uložení argumentů metody. |
| [MethodArgumentTuple< R(C::*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | Definuje n-tici pro uložení argumentů metody. |
| [MulticastDelegateTypeInfo](./multicastdelegatetypeinfo/) | Representuje ukazatel na objekt [TypeInfo](./typeinfo/), který obsahuje informace o třídě MulticastDelegate. |
| [RemoveShared](./removeshared/) | Trait struktury pro odebrání SharedPtr/WeakPtr z typu argumentu. |
| [SByte](./sbyte/) | Obsahuje metody pro práci s 8-bitovým celým číslem. |
| [ScopeGuard](./scopeguard/) | Servisní třída, která poskytuje služby pro spuštění konkrétního funkčního objektu, když instance třídy opustí svůj rozsah. |
| [Single](./single/) | Obsahuje metody pro práci s floating-point číslem s jednoduchou přesností. |
| [TestCompare](./testcompare/) | Servisní struktura poskytující rozhraní pro porovnání kolekcí. |
| [TestTools](./testtools/) | Poskytuje sadu užitečných metod, které kontrolují některé základní vlastnosti různých typů a funkcí. |
| [TestToolsExt](./testtoolsext/) | Společné funkce používané při testování překladu. |
| [TypeInfoPtr](./typeinfoptr/) | Obal pro ukazatel na instanci třídy [TypeInfo](./typeinfo/). Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [UInt16](./uint16/) | Obsahuje metody pro práci s neznamenkovým 16-bitovým celým číslem. |
| [UInt32](./uint32/) | Obsahuje metody pro práci s neznamenkovým 32-bitovým celým číslem. |
| [UInt64](./uint64/) | Obsahuje metody pro práci s neznamenkovým 64-bitovým celým číslem. |
| [ValueTupleTypeInfo](./valuetupletypeinfo/) | Representuje ukazatel na objekt [TypeInfo](./typeinfo/), který obsahuje informace o třídě [ValueTuple](./valuetuple/). |
| [WeakPtrFromTypeParameter](./weakptrfromtypeparameter/) | Trait struktura pro konverzi typu argumentu na slabý ukazatel, pokud se jedná o typ ukazatele. |

## Funkce

| Funkce | Popis |
| --- | --- |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(std::initializer_list\<T\>) | Factory funkce, která vytvoří nový objekt [Array](./array/), naplní jej prvky ze zadaného inicializačního seznamu a vrátí inteligentní ukazatel ukazující na objekt [Array](./array/). |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(Args\&&...) | Factory funkce, která vytvoří nový objekt [Array](./array/) a předá konstruktoru zadané argumenty. |
| std::enable_if\<std::is_integral\<Integral\>::value, [ArrayPtr](./arrayptr/)\<T\>\>::type [MakeArray](./makearray/)(Integral, Args\&&...) | Tovární funkce, která vytvoří nový objekt [Array](./array/) a předá do jeho konstruktoru zadané argumenty. |
| **bool** [operator==](./operator_equal_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) | |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Určuje, zda zadaný objekt [Nullable](./nullable/) představuje hodnotu rovnající se null. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Určuje, zda je zadaná hodnota rovna hodnotě reprezentované objektem [Nullable](./nullable/) použitím [operator==()](./operator_equal_equal/) na tyto hodnoty. |
| **bool** [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | Porovnává rovnost dvou chytrých ukazatelů. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | Kontroluje, zda je chytrý ukazatel null. |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | Porovnání rovnosti chytrého ukazatele s jednoduchým (C) ukazatelem. |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | Porovnání rovnosti chytrého ukazatele s jednoduchým (C) ukazatelem. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(T const\&, std::nullptr_t) | Kontroluje, zda je objekt typu hodnota (přeložená struktura C# atd.) null. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(std::nullptr_t, T const\&) | Kontroluje, zda je objekt typu hodnota (přeložená struktura C# atd.) null. |
| **bool** [operator==](./operator_equal_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) porovnání. |
| **bool** [operator==](./operator_equal_equal/)(T\&, const [String](./string/)\&) | [String](./string/) porovnání. |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) a porovnání řetězce. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [String](./string/)\&) | Kontroluje, zda je řetězec null. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | Určuje, zda jsou URI reprezentované aktuálním a zadaným objektem stejné. |
| **bool** [operator!=](./operator_not_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) | |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Určuje, zda zadaný objekt [Nullable](./nullable/) představuje hodnotu, která není rovna null. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Určuje, zda zadaná hodnota není rovna hodnotě reprezentované objektem [Nullable](./nullable/) použitím [operator!=()](./operator_not_equal/) na tyto hodnoty. |
| **bool** [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | Porovnává nerovnost dvou chytrých ukazatelů. |
| **bool** [operator!=](./operator_not_equal/)([SmartPtr](./smartptr/)\<X\> const\&, std::nullptr_t) | Kontroluje, zda není chytrý ukazatel null. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | Kontroluje, zda není chytrý ukazatel null. |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | Porovnání nerovnosti chytrého ukazatele s jednoduchým (C) ukazatelem. |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | Porovnání rovnosti chytrého ukazatele s jednoduchým (C) ukazatelem. |
| **bool** [operator!=](./operator_not_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) porovnání. |
| **bool** [operator!=](./operator_not_equal/)(T\&, const [String](./string/)\&) | [String](./string/) porovnání. |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) a porovnání řetězce. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [String](./string/)\&) | Kontroluje, zda je řetězec null. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | Určuje, zda URI reprezentované aktuálním a zadaným objektem nejsou stejné. |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) | |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) | |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) | |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) | |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator<](./operator_less/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Vždy vrací false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Určuje, zda je zadaná hodnota menší než hodnota reprezentovaná objektem [Nullable](./nullable/) použitím [operator<()](./operator_less/) na tyto hodnoty. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Vždy vrací false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Určuje, zda je zadaná hodnota menší nebo rovna hodnotě reprezentované objektem [Nullable](./nullable/) použitím [operator<=()](./operator_less_equal/) na tyto hodnoty. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator>](./operator_greater/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Vždy vrací false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Určuje, zda je zadaná hodnota větší než hodnota reprezentovaná objektem [Nullable](./nullable/) použitím [operator>()](./operator_greater/) na tyto hodnoty. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [DateTime](./datetime/)) | |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) | |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | Vždy vrací false. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Určuje, zda je zadaná hodnota větší nebo rovna hodnotě reprezentované objektem [Nullable](./nullable/) použitím [operator>=()](./operator_greater_equal/) na tyto hodnoty. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) | |
| void [PrintTo](./printto/)([DateTime](./datetime/), std::ostream *) | Vypíše hodnotu do ostream. Většinou použito pro ladění. |
| void [PrintTo](./printto/)([DateTimeOffset](./datetimeoffset/), std::ostream *) | Vypíše hodnotu do ostream. Většinou použito pro ladění. |
| void [PrintTo](./printto/)(const [Decimal](./decimal/)\&, ::std::ostream *) | Zapíše hodnotu reprezentovanou zadaným objektem do určeného výstupního proudu. |
| void [PrintTo](./printto/)(const [Details_Exception](./details_exception/)\&, std::ostream *) | Vypíše hodnotu do ostream. Většinou použito pro ladění. |
| void [PrintTo](./printto/)(const [ExceptionWrapper](./exceptionwrapper/)\<T\>\&, std::ostream *) | Vypíše hodnotu do ostream. Většinou použito pro ladění. |
| void [PrintTo](./printto/)(const [Guid](./guid/)\&, std::ostream *) | Vypíše hodnotu do ostream. Většinou použito pro ladění. |
| void [PrintTo](./printto/)(const [Nullable](./nullable/)\<T\>\&, std::ostream *) | Vypíše hodnotu do ostream. Většinou použito pro ladění. |
| void [PrintTo](./printto/)(const [System::Object](./object/)\&, std::ostream *) | Vypíše hodnotu do ostream. Většinou použito pro ladění. |
| std::enable_if_t\<detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | Vypíše hodnotu do ostream. Většinou použito pro ladění. |
| std::enable_if_t<\!detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | Vypíše hodnotu do ostream. Většinou použito pro ladění. |
| void [PrintTo](./printto/)(const [System::String](./string/)\&, std::ostream *) | Vypíše řetězec do ostream. Většinou použito pro ladění. |
| void [PrintTo](./printto/)([TimeSpan](./timespan/), std::ostream *) | Vypíše hodnotu do ostream. Většinou použito pro ladění. |
| void [PrintTo](./printto/)(const [WeakPtr](./weakptr/)\<T\>\&, std::ostream *) | Vypíše hodnotu do ostream. Většinou použito pro ladění. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTime](./datetime/)) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTime](./datetime/)) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTimeOffset](./datetimeoffset/)) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTimeOffset](./datetimeoffset/)) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Decimal](./decimal/)\&) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Decimal](./decimal/)\&) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Exception](./exception/)\&) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Exception](./exception/)\&) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Guid](./guid/)\&) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Guid](./guid/)\&) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Nullable](./nullable/)\<T\>\&) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Nullable](./nullable/)\<T\>\&) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [System::Object](./object/)\&) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [System::Object](./object/)\&) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [OperatingSystem](./operatingsystem/)\&) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [OperatingSystem](./operatingsystem/)\&) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [String](./string/)\&) | Vypíše řetězec na výstupní proud pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [String](./string/)\&) | Vypíše řetězec na výstupní proud. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [TimeSpan](./timespan/)) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [TimeSpan](./timespan/)) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [TypeInfo](./typeinfo/)\&) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [TypeInfo](./typeinfo/)\&) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Version](./version/)\&) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Version](./version/)\&) | Vloží data do proudu. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | Vloží data do proudu pomocí UTF-8 kódování. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | Vloží data do proudu. |
| auto [operator-](./operator_minus/)([DayOfWeek](./dayofweek/), [DayOfWeek](./dayofweek/)) | Vypočítá počet dní mezi dvěma dny v týdnu. |
| [Decimal](./decimal/) [operator-](./operator_minus/)(const T\&, const [Decimal](./decimal/)\&) | Vrací novou instanci třídy [Decimal](./decimal/), která představuje hodnotu vzniklou odečtením hodnoty reprezentované zadaným objektem [Decimal](./decimal/) od zadané hodnoty. |
| MulticastDelegate\<T\> [operator-](./operator_minus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | Odpojí všechny zpětné volání v pravém delegátu od konce seznamu zpětných volání levého delegátu. |
| auto [operator-](./operator_minus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Odečítá nenulovatelné a nulovatelné hodnoty. |
| [Decimal](./decimal/) [operator+](./operator_plus/)(const T\&, const [Decimal](./decimal/)\&) | Vrací novou instanci třídy [Decimal](./decimal/), která představuje hodnotu, jež je součtem zadané hodnoty a hodnoty reprezentované zadaným objektem [Decimal](./decimal/). |
| MulticastDelegate\<T\> [operator+](./operator_plus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | Připojí všechny zpětné volání z pravého delegáta na konec seznamu zpětných volání levého delegáta. |
| auto [operator+](./operator_plus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | Sčítá nenulovatelné a nulovatelné hodnoty. |
| std::enable_if\<[IsStringLiteral](./isstringliteral/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) konkatenace. |
| std::enable_if\<[IsStringPointer](./isstringpointer/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) konkatenace. |
| [String](./string/) [operator+](./operator_plus/)(const char_t, const [String](./string/)\&) | [String](./string/) konkatenace. |
| [Decimal](./decimal/) [operator*](./operator_star/)(const T\&, const [Decimal](./decimal/)\&) | Vrací novou instanci třídy [Decimal](./decimal/), která představuje hodnotu vzniklou násobením zadané hodnoty a hodnoty reprezentované zadaným objektem [Decimal](./decimal/). |
| [Decimal](./decimal/) [operator/](./operator_div/)(const T\&, const [Decimal](./decimal/)\&) | Vrací novou instanci třídy [Decimal](./decimal/), která představuje hodnotu vzniklou dělením zadané hodnoty a hodnoty reprezentované zadaným objektem [Decimal](./decimal/). |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | Vrací referenci na jedinou výchozí konstrukci instance výjimkového typu. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | Vrací referenci na jedinou výchozí konstrukci instance typu, který není výjimkou. |
| T\& [Discard](./discard/)(T\&&) | Vrací výchozí konstrukci dočasné instance zadaného typu, kterou lze použít místo zahazování argumentu '_'. |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [BuildObject](./buildobject/)(Args\&&...) | Vytvoří objekt sdíleného vlastnictví. |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [InitObject](./initobject/)(const [SharedPtr](./sharedptr/)\<T\>\&) | Zahajuje inicializaci objektu sdíleného vlastnictví. |
| Details::ObjectBuilder\<Details::ArrayStorage\<T\>\> [BuildArray](./buildarray/)() | Vytvoří pole. |
| Details::ObjectBuilder\<T\> [Build](./build/)(Args\&&...) | Vytvoří objekt s přímým vlastnictvím. |
| **bool** [Is](./is/)(const ExpressionT\&, ResultT\&) | Implementuje překlad vzoru deklarace 'is'. |
| std::enable_if_t<\!std::is_base_of\<Details::Pattern, ConstantT\>::value, **bool**\> [Is](./is/)(const ExpressionT\&, const ConstantT\&) | Implementuje překlad vzoru konstanty 'is'. |
| std::enable_if_t\<std::is_base_of\<Details::Pattern, A\>::value, **bool**\> [Is](./is/)(const E\&, const A\&) | Funkce shody na nejvyšší úrovni. Použije vzor na hodnotu. |
| static **bool** [IsNull](./isnull/)(const T\&) | Implementuje vzor 'is null'. |
| **bool** [Less](./less/)(const ExpressionT\&, const ConstantT\&) | Implementuje překlad relativního vzoru '<'. |
| **bool** [Greater](./greater/)(const ExpressionT\&, const ConstantT\&) | Implementuje překlad relativního vzoru '>'. |
| **bool** [LEqual](./lequal/)(const ExpressionT\&, const ConstantT\&) | Implementuje překlad relativního vzoru '<='. |
| **bool** [GEqual](./gequal/)(const ExpressionT\&, const ConstantT\&) | Implementuje překlad relativního vzoru '>='. |
| **bool** [Set](./set/)(ExpressionT\&, const ExpressionT\&) | Implementuje překlad vzoru 'var'. |
| **bool** [IsTuple](./istuple/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, **int32_t**) | Kontroluje, zda je objekt n-tice (implementuje rozhraní ITuple). Používá se při implementaci pozičních vzorů. |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&) | Funkce pro získání N-té položky dané n-tice. Přetížení pro základní objekt. |
| auto [Get](./get/)(const T\&) | Funkce pro získání N-té položky dané n-tice. Přetížení pro objekty s metodou Deconstruct. |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<T\>\&) | Funkce pro získání N-té položky dané n-tice. Přetížení pro sdílené ukazatele. |
| auto\& [Get](./get/)(T\&, const [Index](./index/)\&) | Implementace pro výrazy collection[index]. |
| auto [Get](./get/)(T\&, const [Range](./range/)\&) | Vrací výsek ze zadané kolekce definovaný zadaným rozsahem. |
| auto [Get](./get/)(const [ValueTuple](./valuetuple/)\<Args...\>\&) | Získá N-tou položku hodnotové n-tice. |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<T\>\> [MakeYieldEnumerable](./makeyieldenumerable/)(const Details::YieldFunction\<T\>\&) | Vytvoří IEnumerable z funkce yield. |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerator](../system.collections.generic/ienumerator/)\<T\>\> [MakeYieldEnumerator](./makeyieldenumerator/)(const Details::YieldFunction\<T\>\&) | Vytvoří IEnumerator z funkce yield. |
| std::enable_if_t\<Details::is_lambda_void_void\<T\>::value\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | Jediná funkce, která napodobuje chování příkazu try[-catch]-finally v C#. Během překladu příkazu try[-catch]-finally v C# s volbou překladače finally_statement_as_lambda nastavenou na true se tento příkaz překládá na volání této metody. |
| std::enable_if_t\<Details::is_lambda_void_boolref\<T\>::value, **bool**\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | Jediná funkce, která napodobuje chování příkazu try[-catch]-finally v C#. Během překladu příkazu try[-catch]-finally v C# s volbou překladače finally_statement_as_lambda nastavenou na true se tento příkaz překládá na volání této metody. Toto přetížení řeší případ, kdy návratová hodnota funkčního objektu implementujícího část try[-catch] je bool. |
| std::enable_if_t\<Details::is_lambda_nonovoid_boolref\<T\>::value, std::optional\<Details::ResultOf\<T, **bool**\&\>\>\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | Jediná funkce, která napodobuje chování příkazu try[-catch]-finally v C#. Během překladu příkazu try[-catch]-finally v C# s volbou překladače finally_statement_as_lambda nastavenou na true se tento příkaz překládá na volání této metody. Toto přetížení řeší případ, kdy návratová hodnota funkčního objektu implementujícího část try[-catch] je bool&. |
| [DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>::Reference [Ref](./ref/)([DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\&) | Vytvoří referenci na objekt [DynamicWeakPtr](./dynamicweakptr/). Používá se překladačem při předávání argumentů funkcí referencí. |
| T\& [Ref](./ref/)(T\&) | Pomocná funkce pro získání referencí na objekty. Používá se k zajištění, že [System::DynamicWeakPtr](./dynamicweakptr/) aktualizuje referencovaný objekt po přiřazeních. |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | Tato funkční vlastnost obalí enumerable (nebo iterable) objekt, aby mohl být použit v rozsahovém for-loopu. Toto přetížení je určeno pro Enumerable bez metod begin(), end() s argumentem cílového typu pro (auto& value : IterateOver<SomeType>(enumerable)). |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | Tato funkční vlastnost obalí enumerable (nebo iterable) objekt, aby mohl být použit v rozsahovém for-loopu. Toto přetížení je určeno pro Enumerable bez metod begin(), end() s výchozím cílovým typem pro (auto& value : IterateOver(enumerable)) analogicky k následujícímu C# kódu foreach (var value in enumerable). |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | Tato funkční vlastnost obalí enumerable (nebo iterable) objekt, aby mohl být použit v rozsahovém for-loopu. Toto přetížení je určeno pro Enumerable s metodami begin(), end() a výchozím cílovým typem pro (auto& value : IterateOver(enumerable)). |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | Tato funkční vlastnost obalí enumerable (nebo iterable) objekt, aby mohl být použit v rozsahovém for-loopu. Toto přetížení je určeno pro Enumerable s metodami begin(), end() a cílovým typem shodným s původním value_type iterátoru. |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&\!std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, Details::CppIteratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | Tato funkční vlastnost obalí enumerable (nebo iterable) objekt, aby mohl být použit v rozsahovém for-loopu. Toto přetížení je určeno pro Enumerable s metodami begin(), end() a odlišným cílovým typem od původního value_type iterátoru. |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, Details::ValueTypeOfEnumerable\<Enumerable\>, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | Tato funkční vlastnost obalí enumerable (nebo iterable) objekt, aby mohl být použit v rozsahovém for-loopu. Toto přetížení je určeno pro Enumerable this s výchozím cílovým typem. |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | Tato funkční vlastnost obalí enumerable (nebo iterable) objekt, aby mohl být použit v rozsahovém for-loopu. Toto přetížení je určeno pro Enumerable bez metod begin(), end() s argumentem cílového typu pro (auto& value : IterateOver<SomeType>(enumerable)). |
| std::enable_if\<std::is_scalar\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | Vrací hash kód pro zadanou skalární hodnotu. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&[System::IsSmartPtr](./issmartptr/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | Vrací hash kód pro zadaný objekt. |
| std::enable_if\<[System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | Vrací hash kód pro zadaný objekt, který je výjimkou. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\![System::IsSmartPtr](./issmartptr/)\<T\>::value\&&\![System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | Vrací hash kód pro zadaný objekt, který není chytrým ukazatelem ani výjimkou. |
| int [GetHashCode](./gethashcode/)(const std::thread::id\&) | Specializace pro std::thread::id; Vrací hash kód pro zadaný objekt vlákna. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast_noexcept](./cast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Provádí přetypování objektů [SmartPtr](./smartptr/). |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast](./cast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Provádí přetypování objektů [SmartPtr](./smartptr/). |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)(const TFrom\&) | Staré zastaralé přetypování. Bude odstraněno v budoucích verzích. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Provádí dynamické přetypování objektů [SmartPtr](./smartptr/). |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | Provádí dynamické přetypování objektů na objekty výjimky. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast](./dynamiccast/)(const TFrom\&) | Provádí dynamické přetypování výjimečných objektů. |
| std::enable_if<\!std::is_enum\<TTo\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Provádí dynamické přetypování objektů [SmartPtr](./smartptr/). |
| std::enable_if\<std::is_enum\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | Rozbalí zabalený enum pomocí přetypování. |
| [CastResult](./castresult/)\<TTo\>::type [DynamicCast](./dynamiccast/)(std::nullptr_t) | Provádí dynamické přetypování nulových objektů. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&std::is_convertible\<TTo, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom\&) | Provádí dynamické přetypování objektů, které nejsou ukazateli. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | Provádí dynamické přetypování objektů typu Objects na objekty typu Exception. |
| std::enable_if\<std::is_pointer\<TTo\>::value\&&std::is_same\<IntPtr, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom) | Provádí dynamické přetypování z IntPtr na ukazatel. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Provádí statické přetypování objektů [SmartPtr](./smartptr/). |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | Provádí statické přetypování objektů [WeakPtr](./weakptr/). |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)(const TFrom\&) | Provádí statické přetypování objektů typu Exception. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | Provádí statické přetypování objektů typu Objects na objekty typu Exception. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Provádí statické přetypování objektů [SmartPtr](./smartptr/). |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | Provádí statické přetypování objektů [WeakPtr](./weakptr/). |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)(std::nullptr_t) | Provádí statické přetypování nulových objektů. |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(TFrom) | Specializace pro aritmetické typy. |
| std::enable_if\<std::is_same\<TTo, [System::String](./string/)\>::value, TTo\>::type [StaticCast](./staticcast/)(TTo) | Provádí přetypování z [String](./string/) na [String](./string/). |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom *) | Specializace pro aritmetické typy. |
| std::enable_if<\!std::is_same\<TFrom, [System::String](./string/)\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&\!std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | Provádí statické přetypování neukazatelových objektů. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | Provádí statické přetypování objektů typu Exception. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\>) | Provádí statické přetypování objektů typu Objects na objekty typu Exception. |
| [CastResult](./castresult/)\<TTo\>::type [ConstCast](./constcast/)(const [SmartPtr](./smartptr/)\<TFrom\>\&) | Konec zastaralých přetypování. |
| [CastResult](./castresult/)\<TTo\>::type [ForceStaticCast](./forcestaticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | Provádí skutečné statické přetypování objektů [SmartPtr](./smartptr/). |
| [SmartPtr](./smartptr/)\<[Object](./object/)\> [MemberwiseClone](./memberwiseclone/)(T *) | Provádí klonování po jednotlivých částech pomocí kopírovacího konstruktoru. |
| [SharedPtr](./sharedptr/)\<T\> [With](./with/)(const [SharedPtr](./sharedptr/)\<T\>\&, const A\&) | Klonuje referenční záznam a použije na něj inicializační funktor. |
| T [With](./with/)(const T\&, const A\&) | Kopíruje strukturu záznamu a použije na ni inicializační funktor. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se, když jsou zdrojový a cílový typ stejné. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se, když je potřeba jednoduché přetypování podobné konstruktoru. |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro obaly výjimek. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro přetypování objektu na výjimku. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se, když jsou zdroj i výsledek chytré ukazatele (bez explicitního SmartPtr<...> v cílovém typu). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::RawPointer, typename [CastResult](./castresult/)\<std::remove_pointer_t\<Result\>\>::type\> [ExplicitCast](./explicitcast/)(Source) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se při přetypování surového ukazatele na chytrý ukazatel. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se, když jsou zdroj i výsledek chytré ukazatele (s explicitním SmartPtr<...> v cílovém typu). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro rozbalení objektu na nullable. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro zabalení nullable. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro rozbalení nullable objektu. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::EnumBoxing, [SmartPtr](./smartptr/)\<[BoxedValueBase](./boxedvaluebase/)\>\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro zabalení výčtu. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::HeapifyBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro kopírování hodnostních typů na haldu, když má být hodnostní typ odkazován jako chytrý ukazatel (v generikách omezených rozhraním, ale specializovaných strukturou implementující toto rozhraní). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro získání rozhraní z hodnostních typů. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro obecné zabalení. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::StringBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro [System::String](./string/) zabalení. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro rozbalení rozhraní. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Unboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro obecné rozbalení. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro přetypování nullptr. |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí explicitního přetypování. Používá se pro přetypování mezi poli. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se, když je potřeba jednoduché přetypování podobné konstruktoru. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se, když jsou zdrojový a cílový typ stejné. |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se pro obaly výjimek. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se pro přetypování objektu na výjimku. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se, když jsou zdroj i výsledek chytré ukazatele. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se, když jsou zdroj i výsledek chytré ukazatele (s explicitním SmartPtr<...> v cílovém typu). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se pro rozbalení objektu na nullable. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Neplatné rozbalení na typ, který není objektem. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InvalidUnboxing, Result\> [AsCast](./ascast/)(const Source\&) | Neplatné rozbalení na typ, který není objektem. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se pro zabalení nullable objektu. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se pro zabalení běžného objektu. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se pro zabalení běžného objektu. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToString, Result\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se pro rozbalení řetězce. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se pro přetypování nullptr. |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | Přetypuje zdrojový typ na cílový typ pomocí operátoru 'as'. Používá se k přetypování mezi poli. |
| static auto [SafeInvoke](./safeinvoke/)(T0\&&, T1\&&) | Implementace překladu operátoru '?.'. |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::String >](./objecttype_dcolon_gettype_less_system_dcolon_string__greater/)() | Implementuje překlad typeof(). Přetížení pro [String](./string/). |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::DateTime >](./objecttype_dcolon_gettype_less_system_dcolon_datetime__greater/)() | Implementuje překlad typeof(). Přetížení pro [DateTime](./datetime/). |
| **bool** [Equals](./equals/)(const TA\&, const TB\&) | Určuje rovnost dvou hodnot použitím [operator==()](./operator_equal_equal/) na ně. |
| **bool** [Equals< float, float >](./equals_less_float,_float__greater/)(const **float**\&, const **float**\&) | Specializace pro hodnoty s jednoduchou přesností (float). Přestože dva NaN hodnoty s plovoucí řádovou čárkou jsou podle IEC 60559:1989 vždy porovnávány jako nerovné, smlouva pro [System.Object.Equals](./object/equals/) vyžaduje, aby přepsané metody splňovaly požadavky ekvivalenčního operátoru. Proto System.Double.Equals a System.Single.Equals vracejí True při porovnání dvou NaN, zatímco operátor rovnosti v tomto případě vrací False, jak požaduje standard. |
| **bool** [Equals< double, double >](./equals_less_double,_double__greater/)(const **double**\&, const **double**\&) | Specializace pro hodnoty s dvojitou přesností (double). |
| std::enable_if_t<\!std::is_floating_point\<TA\>::value\&&\!std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | Porovnává dvě hodnoty. |
| std::enable_if_t\<std::is_floating_point\<TA\>::value\&&std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | Porovnává dvě hodnoty s plovoucí desetinnou čárkou. |
| **bool** [IsNaN](./isnan/)(const T\&) | Určuje, zda zadaná hodnota je hodnota Not-A-Number. |
| **bool** [IsInfinity](./isinfinity/)(const T\&) | Určuje, zda zadaná hodnota představuje nekonečno. |
| **bool** [IsPositiveInfinity](./ispositiveinfinity/)(const T\&) | Určuje, zda zadaná hodnota představuje kladné nekonečno. |
| **bool** [IsNegativeInfinity](./isnegativeinfinity/)(const T\&) | Určuje, zda zadaná hodnota představuje záporné nekonečno. |
| TTo [CheckedCast](./checkedcast/)(TFrom) | Určuje, zda zadaná hodnota spadá do rozsahu hodnot typu **TTo**, a pokud ano, převádí ji na typ **TTo**. |
| [ScopeGuard](./scopeguard/)\<F\> [MakeScopeGuard](./makescopeguard/)(F) | Tovární funkce, která vytváří instance třídy ScopedGuard. |
| T [setter_wrap](./setter_wrap/)(void(*)(T2), T) | Přetížení pro statické setter funkce s převodem typu. |
| std::enable_if\<std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_wrap](./setter_wrap/)(Host *const, void(HostSet::*)(T2), T) | Přetížení pro setter funkce instance s převodem typu. |
| T [setter_increment_wrap](./setter_increment_wrap/)(T(*)(), void(*)(T)) | Překladač překládá inkrementační výrazy jazyka C# zaměřené na vlastnost třídy, která má definovaný setter a getter, na volání této funkce. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_increment_wrap](./setter_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | Překladač překládá inkrementační výrazy jazyka C# zaměřené na vlastnost třídy, která má definovaný setter a getter, na volání této funkce. |
| T [setter_post_increment_wrap](./setter_post_increment_wrap/)(T(*)(), void(*)(T)) | Překladač překládá post-inkrementační výrazy jazyka C# zaměřené na vlastnost třídy, která má definovaný setter a getter, na volání této funkce. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | Překladač překládá post-inkrementační výrazy jazyka C# zaměřené na vlastnost instance, která má definovaný setter a getter, na volání této funkce (přetížení pro ne-const getter). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | Překladač překládá post-inkrementační výrazy jazyka C# zaměřené na vlastnost instance, která má definovaný setter a getter, na volání této funkce (přetížení pro const getter). |
| T [setter_decrement_wrap](./setter_decrement_wrap/)(T(*)(), void(*)(T)) | Překladač překládá pre-dekrementační výrazy jazyka C# zaměřené na vlastnost třídy, která má definovaný setter a getter, na volání této funkce. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | Překladač překládá pre-dekrementační výrazy jazyka C# zaměřené na vlastnost instance, která má definovaný setter a getter, na volání této funkce (přetížení pro ne-const getter). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | Překladač překládá pre-dekrementační výrazy jazyka C# zaměřené na vlastnost instance, která má definovaný setter a getter, na volání této funkce (přetížení pro const getter). |
| T [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(T(*)(), void(*)(T)) | Překladač překládá post-dekrementační výrazy jazyka C# zaměřené na vlastnost třídy, která má definovaný setter a getter, na volání této funkce. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | Překladač překládá post-dekrementační výrazy jazyka C# zaměřené na vlastnost instance, která má definovaný setter a getter, na volání této funkce (přetížení pro ne-const getter). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | Překladač překládá post-dekrementační výrazy jazyka C# zaměřené na vlastnost instance, která má definovaný setter a getter, na volání této funkce (přetížení pro const getter). |
| std::enable_if<\![IsSmartPtr](./issmartptr/)\<T\>::value, [SmartPtr](./smartptr/)\<T\>\>::type [MakeObject](./makeobject/)(Args\&&...) | Vytvoří objekt na haldě a vrátí na něj sdílený ukazatel. |
| std::enable_if\<[IsSmartPtr](./issmartptr/)\<T\>::value, T\>::type [MakeObject](./makeobject/)(Args\&&...) | Vytvoří objekt na haldě a vrátí na něj sdílený ukazatel. |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(X *) | Převádí surový ukazatel na chytrý ukazatel. |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(const X *) | Převádí surový ukazatel na chytrý ukazatel. Přetížení pro const ukazatele. Užitečné např. při použití proměnné 'this' v metodách C# přeložených jako const. |
| [SmartPtr](./smartptr/)\<Y\> [static_pointer_cast](./static_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | Přetypovává chytré ukazatele pomocí static_cast. |
| [SmartPtr](./smartptr/)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | Přetypovává chytré ukazatele pomocí dynamic_cast. |
| [SmartPtr](./smartptr/)\<Y\> [const_pointer_cast](./const_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | Přetypovává chytré ukazatele pomocí const_cast. |
| T * [get_pointer](./get_pointer/)([System::SmartPtr](./smartptr/)\<T\> const\&) | Získá odkazovaný objekt chytrého ukazatele. |
| std::enable_if<\!System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | Provádí explicitní přetypování prvků zadaného iterovatelného objektu na jiný typ. |
| std::enable_if\<System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | Provádí explicitní přetypování prvků zadaného iterovatelného objektu na jiný typ. |
| std::enable_if_t\<[System::IsSmartPtr](./issmartptr/)\<From\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | Provádí přetypování prvků zadaného pole na jiný typ. Přepis pro případy, kdy From je objekt [SmartPtr](./smartptr/). |
| std::enable_if_t<\![System::IsSmartPtr](./issmartptr/)\<From\>::value\&&[System::IsBoxable](./isboxable/)\<From\>::value\&&std::is_same\<To, [System::SharedPtr](./sharedptr/)\<[Object](./object/)\>\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | Provádí přetypování prvků zadaného pole na jiný typ. Přepis pro případy, kdy From je Boxable a To je [Object](./object/)[]. |
| [SharedPtr](./sharedptr/)\<[Array](./array/)\<To\>\> [DynamicCastArray](./dynamiccastarray/)(const [SharedPtr](./sharedptr/)\<[Array](./array/)\<From\>\>\&) | Provádí přetypování prvků zadaného pole na jiný typ. |
| std::istream\& [operator>>](./operator_greater_greater/)(std::istream\&, [String](./string/)\&) | Získá řetězec ze vstupního proudu pomocí kódování UTF-8. |
| std::wistream\& [operator>>](./operator_greater_greater/)(std::wistream\&, [String](./string/)\&) | Získá řetězec ze vstupního proudu. |
| [TaskPtr](./taskptr/) [MakeAsync](./makeasync/)(const Details::AsyncFunction\&) |  |
| [RTaskPtr](./rtaskptr/)\<T\> [MakeAsync](./makeasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ResultValueTask](../system.threading.tasks/resultvaluetask/)\<T\> [MakeValueAsync](./makevalueasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ValueTask](../system.threading.tasks/valuetask/) [MakeValueAsync](./makevalueasync/)(const Details::AsyncFunction\&) |  |
| [ValueTuple](./valuetuple/)\<Args...\> [MakeTuple](./maketuple/)(Args...) | Vytváří n-tici na zásobníku. |
| [ValueTuple](./valuetuple/)\<Args...\> [TieTuple](./tietuple/)(Args\&&...) | Vytváří n-tici svázanou s některými hodnotami. |
| **bool** [is_vp_test](./is_vp_test/)(const ::testing::TestInfo *) |  |
| **bool** [is_parametrized_test](./is_parametrized_test/)(const ::testing::TestInfo *) |  |
| std::string [ForEachMemberGVName](./foreachmembergvname/)() |  |

## Výčty

| Výčet | Popis |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | Výčet obsahující hodnoty, které představují různé formáty dat kódovaných pomocí base-64. |
| [DateTimeKind](./datetimekind/) | Hodnoty výčtu představují typy data a času. |
| [DayOfWeek](./dayofweek/) | Výčet, který představuje den v týdnu. |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | Určuje umístění proměnné prostředí. |
| [MidpointRounding](./midpointrounding/) | Určuje chování zaokrouhlovacích funkcí. |
| [PlatformID](./platformid/) | Představuje platformu operačního systému. |
| [SmartPtrMode](./smartptrmode/) | [SmartPtr](./smartptr/) typ ukazatele: weak nebo shared. Definuje, zda se ukazatel počítá při rozhodování, zda objekt smazat nebo ne. |
| [StringSplitOptions](./stringsplitoptions/) | Určuje chování při dělení řetězce. |
| [StringComparison](./stringcomparison/) | Definuje styl porovnávání řetězců. |
| [TypeCode](./typecode/) | Představuje typ objektu. |
| [UriKind](./urikind/) | Představuje typy URI. |
| [UriComponents](./uricomponents/) | Představuje komponenty URI. |
| [UriFormat](./uriformat/) | Určuje, jak je URI escapováno. |
| [UriHostNameType](./urihostnametype/) | Představuje typ názvu hostitele. |
| [UriPartial](./uripartial/) | Představuje části URI pro metodu [Uri.GetLeftPart](./uri/getleftpart/). |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [IFormatProviderPtr](./iformatproviderptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::IFormatProvider](./iformatprovider/). |
| [DecoderFallbackPtr](./decoderfallbackptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Text::DecoderFallback](../system.text/decoderfallback/). |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/). |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/). |
| [EncoderFallbackPtr](./encoderfallbackptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Text::EncoderFallback](../system.text/encoderfallback/). |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/). |
| [EncoderPtr](./encoderptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Text::Encoder](../system.text/encoder/). |
| [DecoderPtr](./decoderptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Text::Decoder](../system.text/decoder/). |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/). |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/). |
| [EncodingPtr](./encodingptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Text::Encoding](../system.text/encoding/). |
| [EncodingInfoPtr](./encodinginfoptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Text::EncodingInfo](../system.text/encodinginfo/). |
| [StreamPtr](./streamptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::IO::Stream](../system.io/stream/). |
| [FileStreamPtr](./filestreamptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::IO::FileStream](../system.io/filestream/). |
| [MemoryStreamPtr](./memorystreamptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::IO::MemoryStream](../system.io/memorystream/). |
| [StreamReaderPtr](./streamreaderptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::IO::StreamReader](../system.io/streamreader/). |
| [StreamWriterPtr](./streamwriterptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::IO::StreamWriter](../system.io/streamwriter/). |
| [FileInfoPtr](./fileinfoptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::IO::FileInfo](../system.io/fileinfo/). |
| [FileSystemInfoPtr](./filesysteminfoptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::IO::FileSystemInfo](../system.io/filesysteminfo/). |
| [DirectoryInfoPtr](./directoryinfoptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::IO::DirectoryInfo](../system.io/directoryinfo/). |
| [TaskPtr](./taskptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Threading::Tasks::Task](../system.threading.tasks/task/). |
| [RTaskPtr](./rtaskptr/) | Alias pro chytrý ukazatel, který ukazuje na instanci třídy [System::Threading::Tasks::ResultTask](../system.threading.tasks/resulttask/). |
| [FunctionPtr](./functionptr/) | Alias pro typ funkce s výchozím konvencí volání. |
| [Action](./action/) | Typ delegáta, který odkazuje na metody bez návratové hodnoty. |
| [AggregateException](./aggregateexception/) |  |
| [ByteArrayPtr](./bytearrayptr/) | Alias pro objekt chytrého ukazatele, který ukazuje na pole neznamých 8-bitových celých čísel. |
| [AsyncCallback](./asynccallback/) | Typ delegáta, který představuje metodu volanou po dokončení asynchronní operace. |
| [BadImageFormatException](./badimageformatexception/) | Výjimka, která je vyvolána, když je souborový obrázek dynamické knihovny (DLL) nebo spustitelného programu neplatný. Nikdy neobalujte instance třídy BadImageFormatException do [System::SmartPtr](./smartptr/). |
| [Converter](./converter/) | Reprezentuje ukazatel na invokovatelný entitu, která přijímá jediný argument typu **TInput** a vrací hodnotu typu **TOutput**. |
| [Event](./event/) | Reprezentuje událost – mechanismus, kterým jsou odběratelé informováni o události prostřednictvím volání delegáta. |
| [EventArgsPtr](./eventargsptr/) | Sdílený ukazatel na instanci třídy [EventArgs](./eventargs/). |
| [EventHandler](./eventhandler/) | Reprezentuje metodu, která reaguje na událost a zpracovává ji. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](./smartptr/) k správě objektů tohoto typu. |
| [ExceptionPtr](./exceptionptr/) | Alias typu používaný obalovými výjimkami. |
| [Exception](./exception/) | Alias, který se používá místo Details::Exception. |
| [SystemException](./systemexception/) |  |
| [ApplicationException](./applicationexception/) |  |
| [InvalidOperationException](./invalidoperationexception/) |  |
| [InvalidProgramException](./invalidprogramexception/) |  |
| [InvalidTimeZoneException](./invalidtimezoneexception/) |  |
| [TimeZoneNotFoundException](./timezonenotfoundexception/) |  |
| [ObjectDisposedException](./objectdisposedexception/) |  |
| [NotImplementedException](./notimplementedexception/) |  |
| [NotSupportedException](./notsupportedexception/) |  |
| [PlatformNotSupportedException](./platformnotsupportedexception/) |  |
| [ArgumentException](./argumentexception/) |  |
| [ArgumentNullException](./argumentnullexception/) |  |
| [ArgumentOutOfRangeException](./argumentoutofrangeexception/) |  |
| [FormatException](./formatexception/) |  |
| [UriFormatException](./uriformatexception/) |  |
| [ArithmeticException](./arithmeticexception/) |  |
| [OverflowException](./overflowexception/) |  |
| [DivideByZeroException](./dividebyzeroexception/) |  |
| [OutOfMemoryException](./outofmemoryexception/) |  |
| [IndexOutOfRangeException](./indexoutofrangeexception/) |  |
| [RankException](./rankexception/) |  |
| [InvalidCastException](./invalidcastexception/) |  |
| [NullReferenceException](./nullreferenceexception/) |  |
| [UnauthorizedAccessException](./unauthorizedaccessexception/) |  |
| [MemberAccessException](./memberaccessexception/) |  |
| [MethodAccessException](./methodaccessexception/) |  |
| [OperationCanceledException](./operationcanceledexception/) |  |
| [StackOverflowException](./stackoverflowexception/) |  |
| [TimeoutException](./timeoutexception/) |  |
| [ExecutionEngineException](./executionengineexception/) |  |
| [TypeInitializationException](./typeinitializationexception/) |  |
| [DataMisalignedException](./datamisalignedexception/) |  |
| [IAsyncResultPtr](./iasyncresultptr/) | Sdílený ukazatel na [IAsyncResult](./iasyncresult/). |
| [MakeConstRef_t](./makeconstref_t/) | Pomocný typ pro modifikátor [MakeConstRef](./makeconstref/). |
| [Predicate](./predicate/) | Reprezentuje ukazatel na predikát - volitelný objekt, který přijímá jeden argument a vrací hodnotu typu bool. |
| [ArrayPtr](./arrayptr/) | Alias pro typ 'pointer to array'. |
| [SharedPtr](./sharedptr/) | Alias pro chytrý ukazatel široce používaný v knihovně. |
| [StringComparerPtr](./stringcomparerptr/) | Alias pro sdílený ukazatel na instanci třídy [StringComparer](./stringcomparer/). |
| [TimeZonePtr](./timezoneptr/) | Sdílený ukazatel na instanci třídy [TimeZone](./timezone/). |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | Alias pro sdílený ukazatel na instanci třídy [TimeZoneInfo](./timezoneinfo/). |