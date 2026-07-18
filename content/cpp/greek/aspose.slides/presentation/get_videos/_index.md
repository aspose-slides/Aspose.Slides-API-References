---
title: get_Videos()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. Μόνο για ανάγνωση IVideoCollection.
type: docs
weight: 235
url: /el/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() μέθοδος


Επιστρέφει τη συλλογή όλων των ενσωματωμένων αρχείων βίντεο στην παρουσίαση. Μόνο για ανάγνωση [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Παρατηρήσεις


Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε ενσωματωμένο [Video](../../video/) Frame σε ένα PowerPoint [Presentation](../).
```cpp
// Δημιουργία αντικειμένου Presentation που αντιπροσωπεύει το PPTX
auto pres = System::MakeObject<Presentation>();

// Λήψη της πρώτης διαφάνειας
auto slide = pres->get_Slides()->idx_get(0);

// Ενσωμάτωση βίντεο στην παρουσίαση
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Προσθήκη Video Frame
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Ορισμός βίντεο στο Video Frame
vf->set_EmbeddedVideo(video);
// Ορισμός λειτουργίας αναπαραγωγής και έντασης του βίντεο

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Αποθήκευση του αρχείου PPTX στο δίσκο
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα βίντεο δίνοντας τη διαδρομή του αρχείου βίντεο απευθείας στη μέθοδο AddVideoFrame για το PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε μεγάλο αρχείο μέσω BLOB σε ένα [Presentation](../).
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Δημιουργεί μια νέα παρουσίαση στην οποία θα προστεθεί το βίντεο
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Ας προσθέσουμε το βίντεο στην παρουσίαση - επιλέξαμε τη συμπεριφορά KeepLocked επειδή
// δεν σκοπεύουμε να προσπελάσουμε το αρχείο "veryLargeVideo.avi".
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Αποθηκεύει την παρουσίαση. Καθώς δημιουργείται μια μεγάλη παρουσίαση, η κατανάλωση μνήμης
// παραμένει χαμηλή καθ' όλη τη διάρκεια ζωής του αντικειμένου pres
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
Το παρακάτω παράδειγμα δείχνει πώς να εξάγετε μεγάλο αρχείο μέσω BLOB από το PowerPoint [Presentation](../).
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Δημιουργεί ένα αντικείμενο Presentation, κλειδώνει το αρχείο "hugePresentationWithAudiosAndVideos.pptx".
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Ας αποθηκεύσουμε κάθε βίντεο σε αρχείο. Για να αποτρέψουμε υψηλή χρήση μνήμης, χρειαζόμαστε ένα buffer που θα χρησιμοποιηθεί
// για τη μεταφορά των δεδομένων από το ρεύμα βίντεο της παρουσίασης σε ένα ρεύμα για ένα νεοδημιουργημένο αρχείο βίντεο.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Διατρέχει τα βίντεο
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Ανοίγει το ρεύμα βίντεο της παρουσίασης. Παρακαλώ, σημειώστε ότι αποφεύγουμε σκόπιμα την πρόσβαση σε ιδιότητες
    // όπως video.BinaryData - επειδή αυτή η ιδιότητα επιστρέφει έναν πίνακα bytes που περιέχει ολόκληρο το βίντεο, το οποίο
    // προκαλεί τη φόρτωση bytes στη μνήμη. Χρησιμοποιούμε video.GetStream, που θα επιστρέψει Stream - και δεν
    //  απαιτεί να φορτώσουμε ολόκληρο το βίντεο στη μνήμη.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // Η κατανάλωση μνήμης θα παραμείνει χαμηλή ανεξάρτητα από το μέγεθος του βίντεο ή της παρουσίασης,
}
// Εάν είναι απαραίτητο, μπορείτε να εφαρμόσετε τα ίδια βήματα για αρχεία ήχου.
```
Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε έναν υπερσύνδεσμο σε ένα βίντεο σε ένα PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε [Video](../../video/) Frame με [Video](../../video/) από Πηγή Ιστού σε ένα PowerPoint [Presentation](../).
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Προσθήκη videoFrame
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // Φόρτωση μικρογραφίας
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
Το παρακάτω παράδειγμα δείχνει πώς να εξάγετε [Video](../../video/) από τη διαφάνεια του PowerPoint [Presentation](../).
```cpp
// Δημιουργία αντικειμένου Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
auto presentation = System::MakeObject<Presentation>(u"Video.pptx");

for (auto&& slide : presentation->get_Slides())
{
    for (auto&& shape : slide->get_Shapes())
    {
        if (System::ObjectExt::Is<VideoFrame>(shape))
        {
            System::SharedPtr<IVideoFrame> vf = System::AsCast<IVideoFrame>(shape);
            System::String type = vf->get_EmbeddedVideo()->get_ContentType();
            int32_t ss = type.LastIndexOf(u'/');
            type = type.Remove(0, type.LastIndexOf(u'/') + 1);
            System::ArrayPtr<uint8_t> buffer = vf->get_EmbeddedVideo()->get_BinaryData();
            auto stream = System::MakeObject<System::IO::FileStream>(System::String(u"NewVideo_out.") + type,
                                                                     System::IO::FileMode::Create,
                                                                     System::IO::FileAccess::Write,
                                                                     System::IO::FileShare::Read);
            stream->Write(buffer, 0, buffer->get_Length());
        }
    }
}
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IVideoCollection](../../ivideocollection/)
* Κλάση [Presentation](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)