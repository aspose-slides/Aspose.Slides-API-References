---
title: "System::IO"
second_title: Aspose.Slides pro C++ – reference API
description: 
type: docs
weight: 573
url: /cs/system.io/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | Představuje [System.IO.Stream](./stream/)-podobný obal pro std::basic_iostream a jeho odvozené objekty. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | Představuje [System.IO.Stream](./stream/)-podobný obal pro std::basic_istream a jeho odvozené objekty. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | Představuje [System.IO.Stream](./stream/)-podobný obal pro std::basic_ostream a jeho odvozené objekty. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | Představuje buffer, který obaluje [System::IO::Stream](./stream/)-podobné proudy a umožňuje je použít jako interní buffer proudů podobných std::iostream. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | Představuje obal podobný std::iostream, který používá [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) jako interní buffer. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | Představuje obal podobný std::istream, který používá [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) jako interní buffer. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | Představuje obal podobný std::ostream, který používá [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) jako interní buffer. |
| [BinaryReader](./binaryreader/) | Představuje čtečku, která čte primitivní datové typy jako binární data v konkrétním kódování. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [BinaryWriter](./binarywriter/) | Představuje zapisovač, který zapisuje hodnoty primitivních typů do bytového proudu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [BufferedStream](./bufferedstream/) | Přidává vrstvu bufferování na vrchol jiného proudu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | Výjimka, která je vyhozena, když selže pokus o přístup k souboru, který na disku neexistuje. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu FileNotFoundException. Nikdy nezabaluje instance třídy FileNotFoundException do [System::SmartPtr](../system/smartptr/). |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | Obsahuje metody pro manipulaci s adresáři. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance jakýmkoli způsobem. |
| [DirectoryInfo](./directoryinfo/) | Představuje cestu souborového systému, adresář, na který tato cesta odkazuje, a poskytuje instanční metody pro manipulaci s adresáři. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [File](./file/) | Poskytuje metody pro manipulaci se soubory. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance jakýmkoli způsobem. |
| [FileInfo](./fileinfo/) | Představuje cestu k souboru a soubor, na který tato cesta odkazuje, a poskytuje metody pro jeho manipulaci. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [FileStream](./filestream/) | Představuje souborový proud podporující synchronní i asynchronní operace čtení a zápisu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [FileSystemInfo](./filesysteminfo/) | Základní třída pro [FileInfo](./fileinfo/) a [DirectoryInfo](./directoryinfo/). Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [FileSystemInfoStat](./filesysteminfostat/) | Představuje informace o souboru nebo adresáři. |
| [MemoryStream](./memorystream/) | Představuje proud, který čte z paměti a zapisuje do ní. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [Path](./path/) | Poskytuje metody pro manipulaci s cestami. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance jakýmkoli způsobem. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | Představuje základní třídu pro [System.IO.Stream](./stream/)-podobné obaly. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [Stream](./stream/) | Základní třída pro různé implementace proudů. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [StreamReader](./streamreader/) | Představuje čtečku, která čte znaky z bytového proudu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [StreamWriter](./streamwriter/) | Představuje zapisovač, který zapisuje znaky do bytového proudu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [StringReader](./stringreader/) | Představuje čtečku, která čte znaky z řetězce. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [StringWriter](./stringwriter/) | Implementuje [TextWriter](./textwriter/), který zapisuje informace do řetězce. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [TextReader](./textreader/) | Základní třída pro třídy představující čtečky, které čtou sekvence znaků z různých zdrojů. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [TextWriter](./textwriter/) | Základní třída pro třídy představující zapisovače, které zapisují sekvence znaků do různých cílů. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | Poskytuje přístup k neřízené paměti. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
## Funkce

| Funkce | Popis |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Obalová funkce pro std::basic_istream podobné proudy. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Obalová funkce pro std::basic_ostream podobné proudy. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | Obalová funkce pro std::basic_iostream podobné proudy. |
## Výčty

| Výčet | Popis |
| --- | --- |
| [FileAccess](./fileaccess/) | Určuje typ přístupu při otevírání souboru. |
| [FileAttributes](./fileattributes/) | Reprezentuje atributy adresáře nebo souboru. |
| [FileMode](./filemode/) | Určuje, jak by měl být soubor otevřen. |
| [FileOptions](./fileoptions/) | Reprezentuje pokročilé možnosti pro vytvoření objektu [FileStream](./filestream/). |
| [FileShare](./fileshare/) | Určuje, jaký typ přístupu mohou mít ostatní objekty [FileStream](./filestream/) k otevíranému souboru. |
| [SearchOption](./searchoption/) | Určuje, zda má být hledání provedeno pouze v aktuálním adresáři, nebo v aktuálním adresáři i ve všech jeho podadresářích. |
| [SeekOrigin](./seekorigin/) | Určuje referenční pozici v proudu, relativně k níž je určena pozice, na kterou se má přemístit. |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | Určuje režim I/O operací, které obaly provedou na proudech podobných std::iostream. |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | Určuje, která pozice v proudu je upřednostňována jako společná pozice pro čtení i zápis, když std::basic_iostream a jeho potomci budou mít při vytvoření obalu odlišné pozice pro čtení a zápis. |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | Určuje režim I/O operací, které obaly provedou na proudech podobných [System::IO::Stream](./stream/). |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | Alias pro sdílený ukazatel na tuto třídu. |
| [FileNotFoundException](./filenotfoundexception/) | Výjimka, která je vyhozena, když selže pokus o přístup k souboru, který na disku neexistuje. Nikdy nezabaluje instance třídy FileNotFoundException do [System::SmartPtr](../system/smartptr/). |
| [STDIStreamWrapper](./stdistreamwrapper/) | Specializace [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) pro typy znaků char. |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | Specializace [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) pro typy znaků **wchar_t**. |
| [STDOStreamWrapper](./stdostreamwrapper/) | Specializace [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) pro typy znaků char. |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | Specializace [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) pro typy znaků **wchar_t**. |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | Specializace [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) pro typy znaků char. |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | Specializace [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) pro typy znaků **wchar_t**. |
| [SystemIStreamWrapper](./systemistreamwrapper/) | Specializace [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) pro typy znaků char. |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | Specializace [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) pro typy znaků **wchar_t**. |
| [SystemOStreamWrapper](./systemostreamwrapper/) | Specializace [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) pro typy znaků char. |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | Specializace [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) pro typy znaků **wchar_t**. |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | Specializace [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) pro typy znaků char. |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | Specializace [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) pro typy znaků **wchar_t**. |