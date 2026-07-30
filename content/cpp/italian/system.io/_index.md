---
title: "System::IO"
second_title: "Riferimento API di Aspose.Slides per C++"
description: 
type: docs
weight: 573
url: /it/system.io/
---
## Classes

| Classe | Descrizione |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | Rappresenta un wrapper simile a [System.IO.Stream](./stream/) per std::basic_iostream e i suoi oggetti derivati. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | Rappresenta un wrapper simile a [System.IO.Stream](./stream/) per std::basic_istream e i suoi oggetti derivati. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | Rappresenta un wrapper simile a [System.IO.Stream](./stream/) per std::basic_ostream e i suoi oggetti derivati. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché proverà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | Rappresenta un buffer che avvolge stream simili a [System::IO::Stream](./stream/) e consente di usarli come buffer interno di stream simili a std::iostream. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | Rappresenta un wrapper simile a std::iostream che utilizza [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) come buffer interno. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | Rappresenta un wrapper simile a std::istream che utilizza [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) come buffer interno. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | Rappresenta un wrapper simile a std::ostream che utilizza [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) come buffer interno. |
| [BinaryReader](./binaryreader/) | Rappresenta un lettore che legge tipi di dati primitivi come dati binari in una codifica specifica. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [BinaryWriter](./binarywriter/) | Rappresenta uno scrittore che scrive valori di tipi primitivi in un byte stream. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [BufferedStream](./bufferedstream/) | Aggiunge uno strato di buffering sopra un altro stream. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | L'eccezione che viene generata quando un tentativo di accedere a un file che non esiste sul disco fallisce. Non creare mai istanze di questa classe manualmente. Usa invece la classe FileNotFoundException. Non avvolgere mai le istanze della classe FileNotFoundException in [System::SmartPtr](../system/smartptr/). |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | Contiene metodi per manipolare le directory. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo. |
| [DirectoryInfo](./directoryinfo/) | Rappresenta un percorso nel file system, una directory riferita da questo percorso e fornisce metodi di istanza per manipolare le directory. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [File](./file/) | Fornisce metodi per manipolare i file. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo. |
| [FileInfo](./fileinfo/) | Rappresenta un percorso a un file e il file a cui si riferisce questo percorso e fornisce metodi per manipolarlo. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [FileStream](./filestream/) | Rappresenta un file stream che supporta operazioni di lettura e scrittura sincrone e asincrone. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [FileSystemInfo](./filesysteminfo/) | La classe base per [FileInfo](./fileinfo/) e [DirectoryInfo](./directoryinfo/). Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [FileSystemInfoStat](./filesysteminfostat/) | Rappresenta informazioni su un file o una directory. |
| [MemoryStream](./memorystream/) | Rappresenta uno stream che legge da e scrive in memoria. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [Path](./path/) | Fornisce metodi per manipolare i percorsi. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | Rappresenta una classe base per wrapper simili a [System.IO.Stream](./stream/). Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [Stream](./stream/) | Una classe base per una varietà di implementazioni di stream. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [StreamReader](./streamreader/) | Rappresenta un lettore che legge caratteri da un byte stream. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [StreamWriter](./streamwriter/) | Rappresenta uno scrittore che scrive caratteri in un byte stream. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [StringReader](./stringreader/) | Rappresenta un lettore che legge caratteri da una stringa. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [StringWriter](./stringwriter/) | Implementa un [TextWriter](./textwriter/) che scrive informazioni in una stringa. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [TextReader](./textreader/) | Una classe base per le classi che rappresentano lettori che leggono sequenze di caratteri da diverse fonti. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [TextWriter](./textwriter/) | Una classe base per le classi che rappresentano scrittori che scrivono sequenze di caratteri verso diverse destinazioni. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | Fornisce accesso a memoria non gestita. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento. |

## Functions

| Funzione | Descrizione |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Funzione wrapper per stream simili a std::basic_istream. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Funzione wrapper per stream simili a std::basic_ostream. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | Funzione wrapper per stream simili a std::basic_iostream. |

## Enums

| Enumerazione | Descrizione |
| --- | --- |
| [FileAccess](./fileaccess/) | Specifica il tipo di accesso quando si apre il file. |
| [FileAttributes](./fileattributes/) | Rappresenta gli attributi di una directory o di un file. |
| [FileMode](./filemode/) | Specifica come un file dovrebbe essere aperto. |
| [FileOptions](./fileoptions/) | Rappresenta opzioni avanzate per la creazione dell'oggetto [FileStream](./filestream/). |
| [FileShare](./fileshare/) | Specifica quale tipo di accesso altri oggetti [FileStream](./filestream/) possono avere su un file in fase di apertura. |
| [SearchOption](./searchoption/) | Specifica se la ricerca deve essere eseguita solo nella directory corrente, o nella directory corrente e in tutte le sue sottodirectory. |
| [SeekOrigin](./seekorigin/) | Specifica la posizione di riferimento nello stream rispetto alla quale viene specificata la posizione da cercare. |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | Specifica la modalità di operazioni I/O che i wrapper eseguiranno su stream simili a std::iostream. |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | Determina quale posizione nello stream è preferibile come posizione comune di lettura e scrittura quando std::basic_iostream e i suoi discendenti avranno posizioni di lettura e scrittura diverse al momento della creazione del wrapper. |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | Specifica la modalità di operazioni I/O che i wrapper eseguiranno su stream simili a [System::IO::Stream](./stream/). |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | Un alias per un puntatore condiviso a questa classe. |
| [FileNotFoundException](./filenotfoundexception/) | L'eccezione che viene generata quando un tentativo di accedere a un file che non esiste sul disco fallisce. Non avvolgere mai le istanze della classe FileNotFoundException in [System::SmartPtr](../system/smartptr/). |
| [STDIStreamWrapper](./stdistreamwrapper/) | Specializzazioni di [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) per tipi di carattere char. |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | Specializzazioni di [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) per tipi di carattere **wchar_t**. |
| [STDOStreamWrapper](./stdostreamwrapper/) | Specializzazioni di [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) per tipi di carattere char. |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | Specializzazioni di [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) per tipi di carattere **wchar_t**. |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | Specializzazioni di [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) per tipi di carattere char. |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | Specializzazioni di [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) per tipi di carattere **wchar_t**. |
| [SystemIStreamWrapper](./systemistreamwrapper/) | Specializzazioni di [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) per tipi di carattere char. |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | Specializzazioni di [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) per tipi di carattere **wchar_t**. |
| [SystemOStreamWrapper](./systemostreamwrapper/) | Specializzazioni di [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) per tipi di carattere char. |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | Specializzazioni di [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) per tipi di carattere **wchar_t**. |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | Specializzazioni di [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) per tipi di carattere char. |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | Specializzazioni di [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) per tipi di carattere **wchar_t**. |