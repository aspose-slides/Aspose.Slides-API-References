---
title: "System::IO"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 573
url: /sv/system.io/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | Representerar ett [System.IO.Stream](./stream/)-liknande omslag för std::basic_iostream och dess avledda objekt. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | Representerar ett [System.IO.Stream](./stream/)-liknande omslag för std::basic_istream och dess avledda objekt. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | Representerar ett [System.IO.Stream](./stream/)-liknande omslag för std::basic_ostream och dess avledda objekt. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | Representerar en buffert som omsluter [System::IO::Stream](./stream/)-liknande strömmar och tillåter dem att användas som en intern buffert för std::iostream-liknande strömmar. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | Representerar ett std::iostream-liknande omslag som använde [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) som intern buffert. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | Representerar ett std::istream-liknande omslag som använde [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) som intern buffert. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | Representerar ett std::ostream-liknande omslag som använde [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) som intern buffert. |
| [BinaryReader](./binaryreader/) | Representerar en läsare som läser primitiva datatyper som binär data i en viss kodning. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [BinaryWriter](./binarywriter/) | Representerar en skrivare som skriver värden av primitiva typer till en byte-ström. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [BufferedStream](./bufferedstream/) | Lägger till ett buffreringslager ovanpå en annan ström. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | Undantaget som kastas när ett försök att komma åt en fil som inte finns på disken misslyckas. Skapa aldrig instanser av denna klass manuellt. Använd FileNotFoundException-klass istället. Omslut aldrig instanser av FileNotFoundException-klassen i [System::SmartPtr](../system/smartptr/). |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | Innehåller metoder för att manipulera kataloger. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt. |
| [DirectoryInfo](./directoryinfo/) | Representerar en filsökväg, en katalog som refereras av denna sökväg och tillhandahåller instansmetoder för att manipulera kataloger. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [File](./file/) | Tillhandahåller metoder för att manipulera filer. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt. |
| [FileInfo](./fileinfo/) | Representerar en sökväg till en fil och en fil som refereras av denna sökväg och tillhandahåller metoder för att manipulera den. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [FileStream](./filestream/) | Representerar en filström som stödjer synkrona och asynkrona läs- och skrivoperationer. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [FileSystemInfo](./filesysteminfo/) | Bas-klass för [FileInfo](./fileinfo/) och [DirectoryInfo](./directoryinfo/). Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [FileSystemInfoStat](./filesysteminfostat/) | Representerar information om en fil eller katalog. |
| [MemoryStream](./memorystream/) | Representerar en ström som läser från och skriver till minne. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [Path](./path/) | Tillhandahåller metoder för att manipulera sökvägar. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | Representerar en basklass för [System.IO.Stream](./stream/)-liknande omslag. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [Stream](./stream/) | En basklass för en mängd olika strömä implementationer. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [StreamReader](./streamreader/) | Representerar en läsare som läser tecken från en byte-ström. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [StreamWriter](./streamwriter/) | Representerar en skrivare som skriver tecken till en byte-ström. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [StringReader](./stringreader/) | Representerar en läsare som läser tecken från en sträng. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [StringWriter](./stringwriter/) | Implementerar en [TextWriter](./textwriter/) som skriver information till en sträng. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [TextReader](./textreader/) | En basklass för klasser som representerar läsare som läser sekvenser av tecken från olika källor. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [TextWriter](./textwriter/) | En basklass för klasser som representerar skrivare som skriver sekvenser av tecken till olika destinationer. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | Tillhandahåller åtkomst till ohanterat minne. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körningsfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
## Funktioner

| Funktion | Beskrivning |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Wrapper-funktion för std::basic_istream-liknande strömmar. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Wrapper-funktion för std::basic_ostream-liknande strömmar. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | Wrapper-funktion för std::basic_iostream-liknande strömmar. |
## Uppräkningar

| Enum | Beskrivning |
| --- | --- |
| [FileAccess](./fileaccess/) | Anger åtkomsttypen när filen öppnas. |
| [FileAttributes](./fileattributes/) | Representerar attribut för en katalog eller en fil. |
| [FileMode](./filemode/) | Anger hur en fil ska öppnas. |
| [FileOptions](./fileoptions/) | Representerar avancerade alternativ för att skapa [FileStream](./filestream/)-objekt. |
| [FileShare](./fileshare/) | Anger vilken typ av åtkomst andra [FileStream](./filestream/)-objekt kan ha till en fil som öppnas. |
| [SearchOption](./searchoption/) | Anger att en sökning ska utföras endast i den aktuella katalogen, eller i den aktuella katalogen och alla dess underkataloger. |
| [SeekOrigin](./seekorigin/) | Anger referenspositionen i strömmen relativt vilken den önskade positionen specificeras. |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | Anger lägesinställningen för I/O-operationer som omslag kommer att utföra på std::iostream-liknande strömmar. |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | Bestämmer vilken position i strömmen som är att föredra som gemensam läs- och skrivposition när std::basic_iostream och dess avledda klasser har olika läs- och skrivpositioner vid omslagsskapandet. |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | Anger lägesinställningen för I/O-operationer som omslag kommer att utföra på [System::IO::Stream](./stream/)-liknande strömmar. |
## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | Ett alias för en delad pekare till denna klass. |
| [FileNotFoundException](./filenotfoundexception/) | Undantaget som kastas när ett försök att komma åt en fil som inte finns på disken misslyckas. Omslut aldrig instanser av FileNotFoundException-klassen i [System::SmartPtr](../system/smartptr/). |
| [STDIStreamWrapper](./stdistreamwrapper/) | Specialiseringar av [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) för char-teckentyper. |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | Specialiseringar av [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) för **wchar_t**-teckentyper. |
| [STDOStreamWrapper](./stdostreamwrapper/) | Specialiseringar av [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) för char-teckentyper. |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | Specialiseringar av [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) för **wchar_t**-teckentyper. |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | Specialiseringar av [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) för char-teckentyper. |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | Specialiseringar av [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) för **wchar_t**-teckentyper. |
| [SystemIStreamWrapper](./systemistreamwrapper/) | Specialiseringar av [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) för char-teckentyper. |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | Specialiseringar av [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) för **wchar_t**-teckentyper. |
| [SystemOStreamWrapper](./systemostreamwrapper/) | Specialiseringar av [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) för char-teckentyper. |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | Specialiseringar av [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) för **wchar_t**-teckentyper. |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | Specialiseringar av [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) för char-teckentyper. |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | Specialiseringar av [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) för **wchar_t**-teckentyper. |