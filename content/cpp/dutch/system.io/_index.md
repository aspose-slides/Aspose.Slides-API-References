---
title: "System::IO"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 573
url: /nl/system.io/
---
## Klassen

| Class | Beschrijving |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | Stelt een [System.IO.Stream](./stream/)-achtige wrapper voor std::basic_iostream en de afgeleide objecten voor. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | Stelt een [System.IO.Stream](./stream/)-achtige wrapper voor std::basic_istream en de afgeleide objecten voor. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | Stelt een [System.IO.Stream](./stream/)-achtige wrapper voor std::basic_ostream en de afgeleide objecten voor. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | Stelt een buffer voor die [System::IO::Stream](./stream/)-achtige streams omhult en ze toestaat te worden gebruikt als interne buffer van een std::iostream-achtige stream. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | Stelt een std::iostream-achtige wrapper voor die [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) als interne buffer gebruikt. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | Stelt een std::istream-achtige wrapper voor die [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) als interne buffer gebruikt. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | Stelt een std::ostream-achtige wrapper voor die [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) als interne buffer gebruikt. |
| [BinaryReader](./binaryreader/) | Stelt een lezer voor die primitieve gegevenstypen leest als binaire data in een bepaalde codering. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [BinaryWriter](./binarywriter/) | Stelt een schrijver voor die waarden van primitieve types naar een byte-stream schrijft. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [BufferedStream](./bufferedstream/) | Voegt een bufferlaag toe bovenop een andere stream. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | De exceptie die wordt gegooid wanneer een poging om een niet-bestaand bestand op schijf te benaderen mislukt. Maak nooit handmatig instanties van deze klasse. Gebruik in plaats daarvan de klasse FileNotFoundException. Omhul nooit de instanties van de klasse FileNotFoundException in [System::SmartPtr](../system/smartptr/). |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | Bevat methoden voor het manipuleren van mappen. Dit is een statisch type zonder instantie-services. Je mag nooit op enige wijze instanties ervan creëren. |
| [DirectoryInfo](./directoryinfo/) | Stelt een bestandssysteem-pad voor, een map waarnaar dit pad verwijst, en biedt instantiemethodes voor het manipuleren van mappen. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [File](./file/) | Biedt methoden voor het manipuleren van bestanden. Dit is een statisch type zonder instantie-services. Je mag nooit op enige wijze instanties ervan creëren. |
| [FileInfo](./fileinfo/) | Stelt een pad naar een bestand en een bestand waarnaar dit pad verwijst voor en biedt methoden voor het manipuleren ervan. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [FileStream](./filestream/) | Stelt een bestands-stream voor die synchroon en asynchroon lezen en schrijven ondersteunt. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [FileSystemInfo](./filesysteminfo/) | De basisklasse voor [FileInfo](./fileinfo/) en [DirectoryInfo](./directoryinfo/). Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [FileSystemInfoStat](./filesysteminfostat/) | Stelt informatie over een bestand of map voor. |
| [MemoryStream](./memorystream/) | Stelt een stream voor die van geheugen leest en er naar schrijft. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [Path](./path/) | Biedt methoden voor het manipuleren van paden. Dit is een statisch type zonder instantie-services. Je mag nooit op enige wijze instanties ervan creëren. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | Stelt een basisklasse voor [System.IO.Stream](./stream/)-achtige wrappers voor. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [Stream](./stream/) | Een basisklasse voor diverse stream-implementaties. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [StreamReader](./streamreader/) | Stelt een lezer voor die tekens van een byte-stream leest. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [StreamWriter](./streamwriter/) | Stelt een schrijver voor die tekens naar een byte-stream schrijft. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [StringReader](./stringreader/) | Stelt een lezer voor die tekens van een string leest. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [StringWriter](./stringwriter/) | Implementeert een [TextWriter](./textwriter/) die informatie naar een string schrijft. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [TextReader](./textreader/) | Een basisklasse voor klassen die lezers vertegenwoordigen die reeksen tekens uit verschillende bronnen lezen. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [TextWriter](./textwriter/) | Een basisklasse voor klassen die schrijvers vertegenwoordigen die reeksen tekens naar verschillende bestemmingen schrijven. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | Biedt toegang tot ongemanage geheugen. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven. |

## Functies

| Function | Beschrijving |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Wrapper-functie voor std::basic_istream-achtige streams. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Wrapper-functie voor std::basic_ostream-achtige streams. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | Wrapper-functie voor std::basic_iostream-achtige streams. |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [FileAccess](./fileaccess/) | Specificeert het type toegang bij het openen van het bestand. |
| [FileAttributes](./fileattributes/) | Stelt attributen van een map of een bestand voor. |
| [FileMode](./filemode/) | Specificeert hoe een bestand moet worden geopend. |
| [FileOptions](./fileoptions/) | Stelt geavanceerde opties voor het maken van een [FileStream](./filestream/)-object voor. |
| [FileShare](./fileshare/) | Specificeert welk type toegang andere [FileStream](./filestream/)-objecten kunnen hebben tot een te openen bestand. |
| [SearchOption](./searchoption/) | Specificeert dat een zoekactie alleen in de huidige map moet worden uitgevoerd, of in de huidige map en al haar submappen. |
| [SeekOrigin](./seekorigin/) | Specificeert de referentiepositie in de stream ten opzichte waarvan de te zoeken positie wordt opgegeven. |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | Specificeert de modus van I/O-operaties die wrappers zullen uitvoeren op std::iostream-achtige streams. |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | Bepaalt welke positie in de stream de voorkeur heeft als een gemeenschappelijke lees- en schrijfpositie wanneer std::basic_iostream en zijn afstammelingen op het moment van het maken van de wrapper verschillende lees- en schrijfposities hebben. |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | Specificeert de modus van I/O-operaties die wrappers zullen uitvoeren op [System::IO::Stream](./stream/)-achtige streams. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | Een alias voor een shared pointer naar deze klasse. |
| [FileNotFoundException](./filenotfoundexception/) | De exceptie die wordt gegooid wanneer een poging om een niet-bestaand bestand op schijf te benaderen mislukt. Omhul nooit de instanties van de klasse FileNotFoundException in [System::SmartPtr](../system/smartptr/). |
| [STDIStreamWrapper](./stdistreamwrapper/) | Specialisaties van [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) voor char-teken types. |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | Specialisaties van [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) voor **wchar_t**-teken types. |
| [STDOStreamWrapper](./stdostreamwrapper/) | Specialisaties van [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) voor char-teken types. |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | Specialisaties van [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) voor **wchar_t**-teken types. |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | Specialisaties van [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) voor char-teken types. |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | Specialisaties van [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) voor **wchar_t**-teken types. |
| [SystemIStreamWrapper](./systemistreamwrapper/) | Specialisaties van [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) voor char-teken types. |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | Specialisaties van [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) voor **wchar_t**-teken types. |
| [SystemOStreamWrapper](./systemostreamwrapper/) | Specialisaties van [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) voor char-teken types. |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | Specialisaties van [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) voor **wchar_t**-teken types. |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | Specialisaties van [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) voor char-teken types. |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | Specialisaties van [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) voor **wchar_t**-teken types. |