---
title: Environment
second_title: Referensi API Aspose.Slides untuk C++
description: Layanan lingkungan. Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh pernah membuat instance darinya dengan cara apapun.
type: docs
weight: 1626
url: /id/system/environment/
---
## Struct Lingkungan

[Environment](./) layanan. Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh pernah membuat instance darinya dengan cara apapun.

```cpp
class Environment
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static void [Exit](./exit/)(int) | Menghentikan proses saat ini dan mengembalikan kode keluar yang ditentukan ke sistem operasi. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Mengganti nama variabel lingkungan yang ditemukan dalam string yang ditentukan dengan nilai variabel tersebut dan mengembalikan string yang dihasilkan. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Menghentikan proses saat ini. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Mengembalikan baris perintah yang digunakan untuk memulai proses saat ini. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Mengembalikan jalur ke direktori kerja saat ini. |
| static int [get_ExitCode](./get_exitcode/)() | Mengembalikan kode keluar untuk proses saat ini. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Memeriksa apakah proses shutdown sedang berlangsung. Tidak diimplementasikan. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Mengembalikan true untuk eksekutabel/perpustakaan platform 64-bit. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Mengembalikan nama NetBIOS dari komputer ini. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Mengembalikan string newline yang ditetapkan untuk lingkungan saat ini. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Mengembalikan objek [OperatingSystem](../operatingsystem/) yang berisi informasi tentang sistem operasi saat ini. |
| static int [get_ProcessorCount](./get_processorcount/)() | Mengembalikan jumlah prosesor pada mesin saat ini. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Mengembalikan string yang berisi informasi jejak tumpukan saat ini. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Mengembalikan jalur ke direktori sistem. |
| static int [get_TickCount](./get_tickcount/)() | Mengembalikan jumlah milidetik yang telah berlalu sejak sistem dimulai. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Mengembalikan nama domain jaringan dari pengguna saat ini. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Menentukan apakah proses saat ini berjalan dalam mode interaktif pengguna. |
| static [String](../string/) [get_UserName](./get_username/)() | Mengembalikan nama pengguna yang saat ini masuk ke OS [Windows](../../system.windows/). |
| static [Version](../version/) [get_Version](./get_version/)() | Mengembalikan objek [Version](../version/) yang mewakili informasi tentang versi runtime bahasa umum. Nomor versi yang dikembalikan oleh metode ini bersifat semu dan tidak berarti bahwa semua kelas perpustakaan berperilaku sesuai dengan versi yang dikembalikan. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Mengembalikan jumlah memori fisik yang dipetakan ke konteks proses. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Mengembalikan array yang berisi argumen baris perintah yang digunakan untuk memulai proses saat ini. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Mengembalikan nilai variabel lingkungan yang ditentukan yang terkait dengan proses saat ini. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Mengembalikan nilai variabel lingkungan yang ditentukan dari lokasi yang ditentukan. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Mengembalikan nilai variabel lingkungan yang ditentukan yang terkait dengan proses saat ini. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Mengembalikan kamus yang berisi semua nama variabel lingkungan dan nilai-nilainya yang terkait dengan proses saat ini. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Mengembalikan kamus yang berisi semua nama variabel lingkungan dan nilai-nilainya dari lokasi yang ditentukan. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Mengembalikan nilai variabel lingkungan yang ditentukan yang terkait dengan proses saat ini. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Mengembalikan jalur lengkap ke folder sistem yang ditentukan. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Mengembalikan array yang berisi nama semua drive logis pada komputer saat ini. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Mengembalikan true hanya untuk WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Menetapkan direktori yang ditentukan sebagai direktori kerja saat ini. |
| static void [set_ExitCode](./set_exitcode/)(int) | Menetapkan nilai yang ditentukan sebagai kode keluar untuk proses saat ini. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | TIDAK DIIMPLEMENTASIKAN. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | TIDAK DIIMPLEMENTASIKAN. |

## Enum

| Enum | Deskripsi |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Mewakili folder khusus sistem. |

## Lihat Juga

* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)