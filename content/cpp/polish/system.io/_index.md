---
title: "System::IO"
second_title: Referencja API Aspose.Slides dla C++
description: 
type: docs
weight: 573
url: /pl/system.io/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | Reprezentuje opakowanie podobne do [System.IO.Stream](./stream/) dla std::basic_iostream i jego pochodnych obiektów. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | Reprezentuje opakowanie podobne do [System.IO.Stream](./stream/) dla std::basic_istream i jego pochodnych obiektów. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | Reprezentuje opakowanie podobne do [System.IO.Stream](./stream/) dla std::basic_ostream i jego pochodnych obiektów. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | Reprezentuje bufor, który opakowuje strumienie podobne do [System::IO::Stream](./stream/) i pozwala używać ich jako wewnętrznego bufora strumieni podobnych do std::iostream. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | Reprezentuje opakowanie podobne do std::iostream, które używało [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) jako wewnętrznego bufora. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | Reprezentuje opakowanie podobne do std::istream, które używało [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) jako wewnętrznego bufora. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | Reprezentuje opakowanie podobne do std::ostream, które używało [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) jako wewnętrznego bufora. |
| [BinaryReader](./binaryreader/) | Reprezentuje czytnik, który odczytuje prymitywne typy danych jako dane binarne w określonym kodowaniu. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [BinaryWriter](./binarywriter/) | Reprezentuje pisarz, który zapisuje wartości prymitywnych typów do strumienia bajtowego. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [BufferedStream](./bufferedstream/) | Dodaje warstwę buforowania na wierzchu innego strumienia. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | Wyjątek, który jest rzucany, gdy próba dostępu do nieistniejącego na dysku pliku nie powiedzie się. Nigdy nie twórz ręcznie instancji tej klasy. Użyj zamiast tego klasy FileNotFoundException. Nigdy nie opakowuj instancji klasy FileNotFoundException w [System::SmartPtr](../system/smartptr/). |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | Zawiera metody do manipulacji katalogami. Jest to typ statyczny bez usług instancji. Nigdy nie należy tworzyć jej instancji w żaden sposób. |
| [DirectoryInfo](./directoryinfo/) | Reprezentuje ścieżkę systemu plików, katalog wskazywany przez tę ścieżkę i udostępnia metody do manipulacji katalogami. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [File](./file/) | Udostępnia metody do manipulacji plikami. Jest to typ statyczny bez usług instancji. Nigdy nie należy tworzyć jej instancji w żaden sposób. |
| [FileInfo](./fileinfo/) | Reprezentuje ścieżkę do pliku oraz plik wskazywany przez tę ścieżkę i udostępnia metody do manipulacji nim. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [FileStream](./filestream/) | Reprezentuje strumień plikowy obsługujący synchroniczne i asynchroniczne operacje odczytu i zapisu. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [FileSystemInfo](./filesysteminfo/) | Klasa bazowa dla [FileInfo](./fileinfo/) i [DirectoryInfo](./directoryinfo/). Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [FileSystemInfoStat](./filesysteminfostat/) | Reprezentuje informacje o pliku lub katalogu. |
| [MemoryStream](./memorystream/) | Reprezentuje strumień, który odczytuje z pamięci i zapisuje do pamięci. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [Path](./path/) | Udostępnia metody do manipulacji ścieżkami. Jest to typ statyczny bez usług instancji. Nigdy nie należy tworzyć jej instancji w żaden sposób. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | Reprezentuje klasę bazową dla opakowań podobnych do [System.IO.Stream](./stream/). Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [Stream](./stream/) | Klasa bazowa dla różnorodnych implementacji strumieni. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [StreamReader](./streamreader/) | Reprezentuje czytnik, który odczytuje znaki z strumienia bajtowego. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [StreamWriter](./streamwriter/) | Reprezentuje pisarz, który zapisuje znaki do strumienia bajtowego. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [StringReader](./stringreader/) | Reprezentuje czytnik, który odczytuje znaki z łańcucha znaków. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [StringWriter](./stringwriter/) | Implementuje [TextWriter](./textwriter/), który zapisuje informacje do łańcucha znaków. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [TextReader](./textreader/) | Klasa bazowa dla klas reprezentujących czytniki odczytujące sekwencje znaków z różnych źródeł. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [TextWriter](./textwriter/) | Klasa bazowa dla klas reprezentujących pisarze zapisujące sekwencje znaków do różnych docelowych miejsc. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | Udostępnia dostęp do niezarządzanej pamięci. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonywania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika jako argumentu funkcji. |

## Funkcje

| Funkcja | Opis |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Funkcja opakowująca dla strumieni podobnych do std::basic_istream. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Funkcja opakowująca dla strumieni podobnych do std::basic_ostream. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | Funkcja opakowująca dla strumieni podobnych do std::basic_iostream. |

## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [FileAccess](./fileaccess/) | Określa typ dostępu przy otwieraniu pliku. |
| [FileAttributes](./fileattributes/) | Reprezentuje atrybuty katalogu lub pliku. |
| [FileMode](./filemode/) | Określa, jak plik powinien zostać otwarty. |
| [FileOptions](./fileoptions/) | Reprezentuje zaawansowane opcje tworzenia obiektu [FileStream](./filestream/). |
| [FileShare](./fileshare/) | Określa, jaki rodzaj dostępu inne obiekty [FileStream](./filestream/) mogą mieć do otwieranego pliku. |
| [SearchOption](./searchoption/) | Określa, czy wyszukiwanie ma być przeprowadzone tylko w bieżącym katalogu, czy w bieżącym katalogu i we wszystkich jego podkatalogach. |
| [SeekOrigin](./seekorigin/) | Określa pozycję odniesienia w strumieniu, względem której określana jest pozycja, do której należy przemieścić wskaźnik. |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | Określa tryb operacji I/O, które opakowania będą wykonywać na strumieniach podobnych do std::iostream. |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | Określa, która pozycja w strumieniu jest preferowana jako wspólna pozycja odczytu i zapisu, gdy std::basic_iostream i jego potomki będą miały różne pozycje odczytu i zapisu w momencie tworzenia opakowania. |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | Określa tryb operacji I/O, które opakowania będą wykonywać na strumieniach podobnych do [System::IO::Stream](./stream/). |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | Alias dla wskaźnika współdzielonego do tej klasy. |
| [FileNotFoundException](./filenotfoundexception/) | Wyjątek, który jest rzucany, gdy próba dostępu do nieistniejącego na dysku pliku nie powiedzie się. Nigdy nie opakowuj instancji klasy FileNotFoundException w [System::SmartPtr](../system/smartptr/). |
| [STDIStreamWrapper](./stdistreamwrapper/) | Specjalizacje [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) dla typów znakowych char. |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | Specjalizacje [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) dla typów znakowych **wchar_t**. |
| [STDOStreamWrapper](./stdostreamwrapper/) | Specjalizacje [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) dla typów znakowych char. |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | Specjalizacje [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) dla typów znakowych **wchar_t**. |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | Specjalizacje [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) dla typów znakowych char. |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | Specjalizacje [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) dla typów znakowych **wchar_t**. |
| [SystemIStreamWrapper](./systemistreamwrapper/) | Specjalizacje [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) dla typów znakowych char. |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | Specjalizacje [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) dla typów znakowych **wchar_t**. |
| [SystemOStreamWrapper](./systemostreamwrapper/) | Specjalizacje [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) dla typów znakowych char. |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | Specjalizacje [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) dla typów znakowych **wchar_t**. |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | Specjalizacje [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) dla typów znakowych char. |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | Specjalizacje [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) dla typów znakowych **wchar_t**. |