![http://www.nugen.com](https://www.nugen.com/sites/default/files/logo_0.png)  
[www.nugen.com](http://www.nugen.com) -Change to Tecan branding

#  NuQuant Assay for Qubit
The NuQuant library quantification method accurately measures molar concentrations of NGS libraries. NuQuant library quantification is a proprietary method by which a specific number of fluorescent labels are incorporated into the library molecules during library preparation. Consequently each library molecule has an equivalent number of labels incorporated, regardless of the size of the library fragment. The molar concentration of sequenceable molecules can be directly measured using fluorometers like Qubit® or standard plate readers.

## Downloading the application

### Choose the appropriate instrument file below for the NuQuant product you are using.

Installation instructions follow below.

To download files to your local disk, right-click the `download` link and select "Save as".


| Kit            | Version  | Qubit 2                                                                                                      | Qubit 3 or 4                                                                                                     |
|----------------|----------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| Celero         | PCR      | [download](https://raw.githubusercontent.com/nugentechnologies/NuQuant_Celero/master/Qubit2CeleroPCRv1.qbt)       | [download](https://raw.githubusercontent.com/nugentechnologies/NuQuant_Celero/master/Qubit3and4CeleroPCRv1.qbt)       |
| Universal Plus | PCR      | [download](https://raw.githubusercontent.com/nugentechnologies/NuQuant_UniversalPlus/master/Qubit2UnivPlusv1.qbt) | [download](https://raw.githubusercontent.com/nugentechnologies/NuQuant_UniversalPlus/master/Qubit3and4UnivPlusv1.qbt) |


## Installing the application

### Installing NuQuant on Qubit 2.0

**Note:** NuQuant can only be implemented on Qubit® 2.0 Fluorometers running firmware v3.11 (or higher). For instruments requiring an upgrade, see firmware upgrade instructions [here](https://www.thermofisher.com/us/en/home/industrial/spectroscopy-elemental-isotope-analysis/molecular-spectroscopy/fluorometers/qubit/qubit-technical-resources/previous-qubit-models/qubit-firmware.html).

  1. After downloading the file `Qubit2<KIT NAME>v1.qbt` from the above link, copy it to the root directory of a USB drive (do NOT place the `.qbt` file into a folder in the USB drive). 
     - **Important:** Make sure there is only one `.qbt` file saved to the root directory of the USB drive. Having multiple `.qbt` files present on the USB drive will result in an error when uploading the file.
  2.	Unplug the Qubit power source, insert the USB drive containing the `Qubit2<KIT NAME>v1.qbt` file into the USB drive port of the Qubit® 2.0 Fluorometer, and plug the power back in.
  3.	You will see the message *"Qubit2<KIT NAME>v1.qbt file detected. Do you wish to upload?"* Select `Yes`.
  4.	On the home screen you will now see a button marked `<KIT NAME>`. Select this to perform the NuQuant assay for NuQuant library products.


### Installing NuQuant on Qubit 3.0 and Qubit 4

  1. After downloading the file `Qubit3and4<KIT NAME>.qbt` from the above link, copy it to the root directory of a USB drive (do NOT place the `.qbt` file into a folder in the USB drive). 
     - **Important:** Make sure there is only one `.qbt` file saved to the root directory of the USB drive. Having multiple `.qbt` files present on the USB drive will result in an error when uploading the file.    
  2. Insert the USB drive into the USB drive port of the Qubit® 3.0 or Qubit® 4 Fluorometer. 
  3. Go to the Settings screen and touch `Import new assay`. The instrument searches the USB drive for the `.qbt` file and the Import new assay screen displays "<KIT NAME> NuQuant <version>" under Assay name.
  4. Touch to “<KIT NAME> NuQuant <version>” to select. It will become highlighted. Touch `Next`.
     - Option A: Select a destination folder for the new assay and touch `Save`. Each folder can hold up to 9 assays.
  
     - Option B: Alternatively, touch `New folder` to create a new destination folder. On the New folder screen, touch the `New folder` text field. A keyboard pops up. Using the keyboard, type in the name of the new destination folder. You can use up to 11 characters; spaces at the beginning or the end of the name are not recognized. Touch `Enter`, and then touch `Done` to return to the "Import new assay – Where" screen. The newly created folder will appear in the list of folders. Select the new destination folder and touch `Save`.
  5.	On the verification screen, touch `Done` to complete the import process.
  6.	On the home screen you will now see a button marked <KIT NAME>. Select this to perform the NuQuant assay for NuQuant library products.


### Uninstalling NuQuant on Qubit 2.0

If you wish to remove NuQuant, including the `<KIT NAME>` button from your Qubit home screen, perform the following steps:

  1.	Follow the steps for upgrading firmware (see firmware upgrade instructions.)
  2.	Once you press the `Update` button, a message will appear titled “Updating: Select Assay(s) to Delete”. Select `<KIT NAME>`. The *<KIT NAME>* line will turn gray, indicating it has been selected.
  3.	Click `OK`. 
  4.	Another window will appear with the message *“The selected assay(s) will be deleted. Do you wish to proceed?”*  Click `Yes`. 
  5.	The “Updating firmware…” status bar will appear. After approximately 1 minute, the update will be complete and the NuGEN NuQuant app will have been removed.

### Uninstalling NuQuant from Qubit 3.0 and Qubit 4

  1.	Go to the Settings screen and touch Manage assays.
  2.	Touch `Show/hide Assays`.
  3.  Select the folder which contains NuQuant.
  4.  Next to *`<KIT NAME> NuQuant <version>`*, touch `Delete`, then `Done`.
  5.	The next screen will ask *“This will permanently delete the selected assay(s). Do you wish to continue?"* Touch `OK`.
