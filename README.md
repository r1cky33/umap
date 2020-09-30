# umap

Windows UEFI bootkit that loads a generic driver manual mapper without using a UEFI runtime driver.

# Usage

1. Setup a FAT32 formatted flashdrive with the following filesystem structure: `\EFI\Boot\bootx64.efi` where `bootx64.efi` is the compiled bootkit.

2. Boot from the flashdrive.

# Fork
This build prevents basic memory based detections and dispenses on mapping the drivers header.

# Note
This fork is inteded to be used without the "mapper". The targeted driver directly get mapped at boot time.
