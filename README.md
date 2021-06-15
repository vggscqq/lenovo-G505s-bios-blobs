# Proprietary blobs for lenovo G505s 20255

## Laptop hardware:
* CPU: AMD A8-4500M APU
* GPU: AMD Radeon HD7640G
* FCH: AMD Hudson\*
  * \*I guess it's Hudson, I'm not sure exacly cause Hudson and Bolton has same code base on coreboot repository.
  * \*Exact FCH's chip label: AMD FCH 1410 MADE IN TAIWAN P09698.00 218-0844012. Google has nothing on it. I'll appreciate reports.
  
  ## File list:
  * `0.10.0_1022_7814.bin` | `pci1022,7814.rom` - xHCI blob for FCH and xHCI firmware. Need to USB3 ports work.
  * `vgabios_1002_9903.bin` | `pci1002,9903.rom` - VGABIOS (atombios) blob. Need to integrated GPU work.
