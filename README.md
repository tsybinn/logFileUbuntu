@2ord, May 31
вот лог ядра, если я правильно понял то как раз за минуту до выключения

 16:09:57 tsybinSystem kernel: [    0.000000] microcode: microcode updated early to revision 0xca, date = 2019-10-03
May 31 16:09:57 tsybinSystem kernel: [    0.000000] Linux version 5.3.0-51-generic (buildd@lgw01-amd64-034) (gcc version 9.2.1 20191008 (Ubuntu 9.2.1-9ubuntu2)) #44-Ubuntu SMP Wed Apr 22 21:09:44 UTC 2020 (Ubuntu 5.3.0-51.44-generic 5.3.18)
May 31 16:09:57 tsybinSystem kernel: [    0.000000] Command line: BOOT_IMAGE=/boot/vmlinuz-5.3.0-51-generic root=UUID=ed2264d2-beb2-4d19-b2f1-fa66a1e06568 ro quiet splash vt.handoff=7
May 31 16:09:57 tsybinSystem kernel: [    0.000000] KERNEL supported cpus:
May 31 16:09:57 tsybinSystem kernel: [    0.000000]   Intel GenuineIntel
May 31 16:09:57 tsybinSystem kernel: [    0.000000]   AMD AuthenticAMD
May 31 16:09:57 tsybinSystem kernel: [    0.000000]   Hygon HygonGenuine
May 31 16:09:57 tsybinSystem kernel: [    0.000000]   Centaur CentaurHauls
May 31 16:09:57 tsybinSystem kernel: [    0.000000]   zhaoxin   Shanghai  
May 31 16:09:57 tsybinSystem kernel: [    0.000000] x86/fpu: Supporting XSAVE feature 0x001: 'x87 floating point registers'
May 31 16:09:57 tsybinSystem kernel: [    0.000000] x86/fpu: Supporting XSAVE feature 0x002: 'SSE registers'
May 31 16:09:57 tsybinSystem kernel: [    0.000000] x86/fpu: Supporting XSAVE feature 0x004: 'AVX registers'
May 31 16:09:57 tsybinSystem kernel: [    0.000000] x86/fpu: Supporting XSAVE feature 0x008: 'MPX bounds registers'
May 31 16:09:57 tsybinSystem kernel: [    0.000000] x86/fpu: Supporting XSAVE feature 0x010: 'MPX CSR'
May 31 16:09:57 tsybinSystem kernel: [    0.000000] x86/fpu: xstate_offset[2]:  576, xstate_sizes[2]:  256
May 31 16:09:57 tsybinSystem kernel: [    0.000000] x86/fpu: xstate_offset[3]:  832, xstate_sizes[3]:   64
May 31 16:09:57 tsybinSystem kernel: [    0.000000] x86/fpu: xstate_offset[4]:  896, xstate_sizes[4]:   64
May 31 16:09:57 tsybinSystem kernel: [    0.000000] x86/fpu: Enabled xstate features 0x1f, context size is 960 bytes, using 'compacted' format.
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-provided physical RAM map:
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x0000000000000000-0x000000000009c3ff] usable
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x000000000009c400-0x000000000009ffff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000000e0000-0x00000000000fffff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x0000000000100000-0x00000000b23c9fff] usable
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000b23ca000-0x00000000b2402fff] ACPI data
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000b2403000-0x00000000b3e14fff] usable
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000b3e15000-0x00000000b3e15fff] ACPI NVS
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000b3e16000-0x00000000b3e16fff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000b3e17000-0x00000000c0956fff] usable
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000c0957000-0x00000000c21affff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000c21b0000-0x00000000c21c3fff] ACPI data
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000c21c4000-0x00000000c22fdfff] usable
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000c22fe000-0x00000000c2625fff] ACPI NVS
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000c2626000-0x00000000c2fa1fff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000c2fa2000-0x00000000c2ffffff] usable
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000c3000000-0x00000000c7ffffff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000f8000000-0x00000000fbffffff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000fe000000-0x00000000fe010fff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000fec00000-0x00000000fec00fff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000fed00000-0x00000000fed00fff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000fee00000-0x00000000fee00fff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x00000000ff000000-0x00000000ffffffff] reserved
May 31 16:09:57 tsybinSystem kernel: [    0.000000] BIOS-e820: [mem 0x0000000100000000-0x0000000236ffffff] usable
May 31 16:09:57 tsybinSystem kernel: [    0.000000] NX (Execute Disable) protection: active
May 31 16:09:57 tsybinSystem kernel: [    0.000000] SMBIOS 3.1.1 present.
May 31 16:09:57 tsybinSystem kernel: [    0.000000] DMI: System manufacturer System Product Name/PRIME H310M-R R2.0, BIOS 1002 05/24/2019
May 31 16:09:57 tsybinSystem kernel: [    0.000000] tsc: Detected 3600.000 MHz processor
May 31 16:09:57 tsybinSystem kernel: [    0.001412] e820: update [mem 0x00000000-0x00000fff] usable ==> reserved
May 31 16:09:57 tsybinSystem kernel: [    0.001413] e820: remove [mem 0x000a0000-0x000fffff] usable
May 31 16:09:57 tsybinSystem kernel: [    0.001418] last_pfn = 0x237000 max_arch_pfn = 0x400000000
May 31 16:09:57 tsybinSystem kernel: [    0.001421] MTRR default type: write-back
May 31 16:09:57 tsybinSystem kernel: [    0.001421] MTRR fixed ranges enabled:
May 31 16:09:57 tsybinSystem kernel: [    0.001422]   00000-9FFFF write-back
May 31 16:09:57 tsybinSystem kernel: [    0.001423]   A0000-BFFFF uncachable
May 31 16:09:57 tsybinSystem kernel: [    0.001423]   C0000-FFFFF write-protect
May 31 16:09:57 tsybinSystem kernel: [    0.001424] MTRR variable ranges enabled:
May 31 16:09:57 tsybinSystem kernel: [    0.001425]   0 base 00E0000000 mask 7FE0000000 uncachable
May 31 16:09:57 tsybinSystem kernel: [    0.001425]   1 base 00D0000000 mask 7FF0000000 uncachable
May 31 16:09:57 tsybinSystem kernel: [    0.001426]   2 base 00C8000000 mask 7FF8000000 uncachable
May 31 16:09:57 tsybinSystem kernel: [    0.001426]   3 base 00C4000000 mask 7FFC000000 uncachable
May 31 16:09:57 tsybinSystem kernel: [    0.001427]   4 base 00C3800000 mask 7FFF800000 uncachable
May 31 16:09:57 tsybinSystem kernel: [    0.001427]   5 disabled
May 31 16:09:57 tsybinSystem kernel: [    0.001427]   6 disabled
May 31 16:09:57 tsybinSystem kernel: [    0.001428]   7 disabled
May 31 16:09:57 tsybinSystem kernel: [    0.001428]   8 disabled
May 31 16:09:57 tsybinSystem kernel: [    0.001428]   9 disabled
May 31 16:09:57 tsybinSystem kernel: [    0.001693] x86/PAT: Configuration [0-7]: WB  WC  UC- UC  WB  WP  UC- WT  
May 31 16:09:57 tsybinSystem kernel: [    0.001809] last_pfn = 0xc3000 max_arch_pfn = 0x400000000
May 31 16:09:57 tsybinSystem kernel: [    0.007452] found SMP MP-table at [mem 0x000fcd80-0x000fcd8f]
May 31 16:09:57 tsybinSystem kernel: [    0.007506] check: Scanning 1 areas for low memory corruption
May 31 16:09:57 tsybinSystem kernel: [    0.007509] Using GB pages for direct mapping
May 31 16:09:57 tsybinSystem kernel: [    0.007510] BRK [0x231001000, 0x231001fff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007511] BRK [0x231002000, 0x231002fff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007512] BRK [0x231003000, 0x231003fff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007538] BRK [0x231004000, 0x231004fff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007539] BRK [0x231005000, 0x231005fff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007662] BRK [0x231006000, 0x231006fff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007684] BRK [0x231007000, 0x231007fff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007707] BRK [0x231008000, 0x231008fff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007739] BRK [0x231009000, 0x231009fff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007782] BRK [0x23100a000, 0x23100afff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007822] BRK [0x23100b000, 0x23100bfff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007876] BRK [0x23100c000, 0x23100cfff] PGTABLE
May 31 16:09:57 tsybinSystem kernel: [    0.007993] RAMDISK: [mem 0x32491000-0x3523ffff]
May 31 16:09:57 tsybinSystem kernel: [    0.007999] ACPI: Early table checksum verification disabled
May 31 16:09:57 tsybinSystem kernel: [    0.008001] ACPI: RSDP 0x00000000000F05B0 000024 (v02 ALASKA)
May 31 16:09:57 tsybinSystem kernel: [    0.008003] ACPI: XSDT 0x00000000B23CA0B0 0000D4 (v01 ALASKA A M I    01072009 AMI  00010013)
May 31 16:09:57 tsybinSystem kernel: [    0.008007] ACPI: FACP 0x00000000B23F56E0 000114 (v06 ALASKA A M I    01072009 AMI  00010013)
May 31 16:09:57 tsybinSystem kernel: [    0.008010] ACPI: DSDT 0x00000000B23CA218 02B4C7 (v02 ALASKA A M I    01072009 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008012] ACPI: FACS 0x00000000C2625F00 000040
May 31 16:09:57 tsybinSystem kernel: [    0.008014] ACPI: APIC 0x00000000B23F57F8 000084 (v03 ALASKA A M I    01072009 AMI  00010013)
May 31 16:09:57 tsybinSystem kernel: [    0.008016] ACPI: FPDT 0x00000000B23F5880 000044 (v01 ALASKA A M I    01072009 AMI  00010013)
May 31 16:09:57 tsybinSystem kernel: [    0.008017] ACPI: FIDT 0x00000000B23F58C8 00009C (v01 ALASKA A M I    01072009 AMI  00010013)
May 31 16:09:57 tsybinSystem kernel: [    0.008019] ACPI: WSMT 0x00000000B2402768 000028 (v01 ALASKA A M I    01072009 AMI  00010013)
May 31 16:09:57 tsybinSystem kernel: [    0.008021] ACPI: MCFG 0x00000000B23F59C0 00003C (v01 ALASKA A M I    01072009 MSFT 00000097)
May 31 16:09:57 tsybinSystem kernel: [    0.008023] ACPI: SSDT 0x00000000B23F5A00 0003A3 (v01 SataRe SataTabl 00001000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008025] ACPI: SSDT 0x00000000B23F5DA8 003052 (v02 SaSsdt SaSsdt   00003000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008026] ACPI: SSDT 0x00000000B23F8E00 002743 (v02 PegSsd PegSsdt  00001000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008028] ACPI: HPET 0x00000000B23FB548 000038 (v01 INTEL  KBL      00000001 MSFT 0000005F)
May 31 16:09:57 tsybinSystem kernel: [    0.008030] ACPI: SSDT 0x00000000B23FB580 0011AA (v02 INTEL  Ther_Rvp 00001000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008032] ACPI: SSDT 0x00000000B23FC730 000B1B (v02 INTEL  xh_rvp08 00000000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008034] ACPI: UEFI 0x00000000B23FD250 000048 (v01 ALASKA A M I    00000002      01000013)
May 31 16:09:57 tsybinSystem kernel: [    0.008035] ACPI: SSDT 0x00000000B23FD298 0017AE (v02 CpuRef CpuSsdt  00003000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008037] ACPI: LPIT 0x00000000B23FEA48 000094 (v01 INTEL  KBL      00000000 MSFT 0000005F)
May 31 16:09:57 tsybinSystem kernel: [    0.008039] ACPI: SSDT 0x00000000B23FEAE0 000141 (v02 INTEL  HdaDsp   00000000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008041] ACPI: SSDT 0x00000000B23FEC28 00029F (v02 INTEL  sensrhub 00000000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008042] ACPI: SSDT 0x00000000B23FEEC8 003002 (v02 INTEL  PtidDevc 00001000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008044] ACPI: SSDT 0x00000000B2401ED0 000517 (v02 INTEL  TbtTypeC 00000000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008046] ACPI: SSDT 0x00000000B24023E8 0002E9 (v02 INTEL  Wwan     00000001 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.008048] ACPI: DBGP 0x00000000B24026D8 000034 (v01 INTEL           00000002 MSFT 0000005F)
May 31 16:09:57 tsybinSystem kernel: [    0.008049] ACPI: DBG2 0x00000000B2402710 000054 (v00 INTEL           00000002 MSFT 0000005F)
May 31 16:09:57 tsybinSystem kernel: [    0.008056] ACPI: Local APIC address 0xfee00000
May 31 16:09:57 tsybinSystem kernel: [    0.008189] No NUMA configuration found
May 31 16:09:57 tsybinSystem kernel: [    0.008189] Faking a node at [mem 0x0000000000000000-0x0000000236ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.008195] NODE_DATA(0) allocated [mem 0x236fd3000-0x236ffdfff]
May 31 16:09:57 tsybinSystem kernel: [    0.008328] Zone ranges:
May 31 16:09:57 tsybinSystem kernel: [    0.008329]   DMA      [mem 0x0000000000001000-0x0000000000ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.008330]   DMA32    [mem 0x0000000001000000-0x00000000ffffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.008330]   Normal   [mem 0x0000000100000000-0x0000000236ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.008331]   Device   empty
May 31 16:09:57 tsybinSystem kernel: [    0.008332] Movable zone start for each node
May 31 16:09:57 tsybinSystem kernel: [    0.008334] Early memory node ranges
May 31 16:09:57 tsybinSystem kernel: [    0.008334]   node   0: [mem 0x0000000000001000-0x000000000009bfff]
May 31 16:09:57 tsybinSystem kernel: [    0.008335]   node   0: [mem 0x0000000000100000-0x00000000b23c9fff]
May 31 16:09:57 tsybinSystem kernel: [    0.008335]   node   0: [mem 0x00000000b2403000-0x00000000b3e14fff]
May 31 16:09:57 tsybinSystem kernel: [    0.008336]   node   0: [mem 0x00000000b3e17000-0x00000000c0956fff]
May 31 16:09:57 tsybinSystem kernel: [    0.008336]   node   0: [mem 0x00000000c21c4000-0x00000000c22fdfff]
May 31 16:09:57 tsybinSystem kernel: [    0.008337]   node   0: [mem 0x00000000c2fa2000-0x00000000c2ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.008337]   node   0: [mem 0x0000000100000000-0x0000000236ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.008514] Zeroed struct page in unavailable ranges: 34225 pages
May 31 16:09:57 tsybinSystem kernel: [    0.008515] Initmem setup node 0 [mem 0x0000000000001000-0x0000000236ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.008516] On node 0 totalpages: 2062927
May 31 16:09:57 tsybinSystem kernel: [    0.008517]   DMA zone: 64 pages used for memmap
May 31 16:09:57 tsybinSystem kernel: [    0.008517]   DMA zone: 21 pages reserved
May 31 16:09:57 tsybinSystem kernel: [    0.008518]   DMA zone: 3995 pages, LIFO batch:0
May 31 16:09:57 tsybinSystem kernel: [    0.008553]   DMA32 zone: 12267 pages used for memmap
May 31 16:09:57 tsybinSystem kernel: [    0.008554]   DMA32 zone: 785076 pages, LIFO batch:63
May 31 16:09:57 tsybinSystem kernel: [    0.017228]   Normal zone: 19904 pages used for memmap
May 31 16:09:57 tsybinSystem kernel: [    0.017228]   Normal zone: 1273856 pages, LIFO batch:63
May 31 16:09:57 tsybinSystem kernel: [    0.029433] Reserving Intel graphics memory at [mem 0xc4000000-0xc7ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029587] ACPI: PM-Timer IO Port: 0x1808
May 31 16:09:57 tsybinSystem kernel: [    0.029588] ACPI: Local APIC address 0xfee00000
May 31 16:09:57 tsybinSystem kernel: [    0.029592] ACPI: LAPIC_NMI (acpi_id[0x01] high edge lint[0x1])
May 31 16:09:57 tsybinSystem kernel: [    0.029593] ACPI: LAPIC_NMI (acpi_id[0x02] high edge lint[0x1])
May 31 16:09:57 tsybinSystem kernel: [    0.029593] ACPI: LAPIC_NMI (acpi_id[0x03] high edge lint[0x1])
May 31 16:09:57 tsybinSystem kernel: [    0.029593] ACPI: LAPIC_NMI (acpi_id[0x04] high edge lint[0x1])
May 31 16:09:57 tsybinSystem kernel: [    0.029619] IOAPIC[0]: apic_id 2, version 32, address 0xfec00000, GSI 0-119
May 31 16:09:57 tsybinSystem kernel: [    0.029621] ACPI: INT_SRC_OVR (bus 0 bus_irq 0 global_irq 2 dfl dfl)
May 31 16:09:57 tsybinSystem kernel: [    0.029621] ACPI: INT_SRC_OVR (bus 0 bus_irq 9 global_irq 9 high level)
May 31 16:09:57 tsybinSystem kernel: [    0.029622] ACPI: IRQ0 used by override.
May 31 16:09:57 tsybinSystem kernel: [    0.029623] ACPI: IRQ9 used by override.
May 31 16:09:57 tsybinSystem kernel: [    0.029624] Using ACPI (MADT) for SMP configuration information
May 31 16:09:57 tsybinSystem kernel: [    0.029625] ACPI: HPET id: 0x8086a201 base: 0xfed00000
May 31 16:09:57 tsybinSystem kernel: [    0.029627] smpboot: Allowing 4 CPUs, 0 hotplug CPUs
May 31 16:09:57 tsybinSystem kernel: [    0.029641] PM: Registered nosave memory: [mem 0x00000000-0x00000fff]
May 31 16:09:57 tsybinSystem kernel: [    0.029642] PM: Registered nosave memory: [mem 0x0009c000-0x0009cfff]
May 31 16:09:57 tsybinSystem kernel: [    0.029643] PM: Registered nosave memory: [mem 0x0009d000-0x0009ffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029643] PM: Registered nosave memory: [mem 0x000a0000-0x000dffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029643] PM: Registered nosave memory: [mem 0x000e0000-0x000fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029644] PM: Registered nosave memory: [mem 0xb23ca000-0xb2402fff]
May 31 16:09:57 tsybinSystem kernel: [    0.029645] PM: Registered nosave memory: [mem 0xb3e15000-0xb3e15fff]
May 31 16:09:57 tsybinSystem kernel: [    0.029646] PM: Registered nosave memory: [mem 0xb3e16000-0xb3e16fff]
May 31 16:09:57 tsybinSystem kernel: [    0.029647] PM: Registered nosave memory: [mem 0xc0957000-0xc21affff]
May 31 16:09:57 tsybinSystem kernel: [    0.029647] PM: Registered nosave memory: [mem 0xc21b0000-0xc21c3fff]
May 31 16:09:57 tsybinSystem kernel: [    0.029648] PM: Registered nosave memory: [mem 0xc22fe000-0xc2625fff]
May 31 16:09:57 tsybinSystem kernel: [    0.029648] PM: Registered nosave memory: [mem 0xc2626000-0xc2fa1fff]
May 31 16:09:57 tsybinSystem kernel: [    0.029649] PM: Registered nosave memory: [mem 0xc3000000-0xc7ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029650] PM: Registered nosave memory: [mem 0xc8000000-0xf7ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029650] PM: Registered nosave memory: [mem 0xf8000000-0xfbffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029650] PM: Registered nosave memory: [mem 0xfc000000-0xfdffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029651] PM: Registered nosave memory: [mem 0xfe000000-0xfe010fff]
May 31 16:09:57 tsybinSystem kernel: [    0.029651] PM: Registered nosave memory: [mem 0xfe011000-0xfebfffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029651] PM: Registered nosave memory: [mem 0xfec00000-0xfec00fff]
May 31 16:09:57 tsybinSystem kernel: [    0.029652] PM: Registered nosave memory: [mem 0xfec01000-0xfecfffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029652] PM: Registered nosave memory: [mem 0xfed00000-0xfed00fff]
May 31 16:09:57 tsybinSystem kernel: [    0.029652] PM: Registered nosave memory: [mem 0xfed01000-0xfedfffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029653] PM: Registered nosave memory: [mem 0xfee00000-0xfee00fff]
May 31 16:09:57 tsybinSystem kernel: [    0.029653] PM: Registered nosave memory: [mem 0xfee01000-0xfeffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029653] PM: Registered nosave memory: [mem 0xff000000-0xffffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.029654] [mem 0xc8000000-0xf7ffffff] available for PCI devices
May 31 16:09:57 tsybinSystem kernel: [    0.029655] Booting paravirtualized kernel on bare hardware
May 31 16:09:57 tsybinSystem kernel: [    0.029657] clocksource: refined-jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 7645519600211568 ns
May 31 16:09:57 tsybinSystem kernel: [    0.029661] setup_percpu: NR_CPUS:8192 nr_cpumask_bits:4 nr_cpu_ids:4 nr_node_ids:1
May 31 16:09:57 tsybinSystem kernel: [    0.029833] percpu: Embedded 54 pages/cpu s184320 r8192 d28672 u524288
May 31 16:09:57 tsybinSystem kernel: [    0.029837] pcpu-alloc: s184320 r8192 d28672 u524288 alloc=1*2097152
May 31 16:09:57 tsybinSystem kernel: [    0.029838] pcpu-alloc: [0] 0 1 2 3 
May 31 16:09:57 tsybinSystem kernel: [    0.029856] Built 1 zonelists, mobility grouping on.  Total pages: 2030671
May 31 16:09:57 tsybinSystem kernel: [    0.029856] Policy zone: Normal
May 31 16:09:57 tsybinSystem kernel: [    0.029857] Kernel command line: BOOT_IMAGE=/boot/vmlinuz-5.3.0-51-generic root=UUID=ed2264d2-beb2-4d19-b2f1-fa66a1e06568 ro quiet splash vt.handoff=7
May 31 16:09:57 tsybinSystem kernel: [    0.030352] Dentry cache hash table entries: 1048576 (order: 11, 8388608 bytes, linear)
May 31 16:09:57 tsybinSystem kernel: [    0.030590] Inode-cache hash table entries: 524288 (order: 10, 4194304 bytes, linear)
May 31 16:09:57 tsybinSystem kernel: [    0.030624] mem auto-init: stack:off, heap alloc:on, heap free:off
May 31 16:09:57 tsybinSystem kernel: [    0.034633] Calgary: detecting Calgary via BIOS EBDA area
May 31 16:09:57 tsybinSystem kernel: [    0.034634] Calgary: Unable to locate Rio Grande table in EBDA - bailing!
May 31 16:09:57 tsybinSystem kernel: [    0.057015] Memory: 7961644K/8251708K available (14339K kernel code, 2387K rwdata, 4728K rodata, 2676K init, 5044K bss, 290064K reserved, 0K cma-reserved)
May 31 16:09:57 tsybinSystem kernel: [    0.057102] SLUB: HWalign=64, Order=0-3, MinObjects=0, CPUs=4, Nodes=1
May 31 16:09:57 tsybinSystem kernel: [    0.057110] Kernel/User page tables isolation: enabled
May 31 16:09:57 tsybinSystem kernel: [    0.057120] ftrace: allocating 43602 entries in 171 pages
May 31 16:09:57 tsybinSystem kernel: [    0.069067] rcu: Hierarchical RCU implementation.
May 31 16:09:57 tsybinSystem kernel: [    0.069068] rcu: 	RCU restricting CPUs from NR_CPUS=8192 to nr_cpu_ids=4.
May 31 16:09:57 tsybinSystem kernel: [    0.069068] 	Tasks RCU enabled.
May 31 16:09:57 tsybinSystem kernel: [    0.069069] rcu: RCU calculated value of scheduler-enlistment delay is 25 jiffies.
May 31 16:09:57 tsybinSystem kernel: [    0.069069] rcu: Adjusting geometry for rcu_fanout_leaf=16, nr_cpu_ids=4
May 31 16:09:57 tsybinSystem kernel: [    0.071391] NR_IRQS: 524544, nr_irqs: 1024, preallocated irqs: 16
May 31 16:09:57 tsybinSystem kernel: [    0.071700] random: crng done (trusting CPU's manufacturer)
May 31 16:09:57 tsybinSystem kernel: [    0.071717] vt handoff: transparent VT on vt#7
May 31 16:09:57 tsybinSystem kernel: [    0.071723] Console: colour dummy device 80x25
May 31 16:09:57 tsybinSystem kernel: [    0.071726] printk: console [tty0] enabled
May 31 16:09:57 tsybinSystem kernel: [    0.071737] ACPI: Core revision 20190703
May 31 16:09:57 tsybinSystem kernel: [    0.071979] clocksource: hpet: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 79635855245 ns
May 31 16:09:57 tsybinSystem kernel: [    0.072044] APIC: Switch to symmetric I/O mode setup
May 31 16:09:57 tsybinSystem kernel: [    0.073243] x2apic: IRQ remapping doesn't support X2APIC mode
May 31 16:09:57 tsybinSystem kernel: [    0.077481] ..TIMER: vector=0x30 apic1=0 pin1=2 apic2=-1 pin2=-1
May 31 16:09:57 tsybinSystem kernel: [    0.096018] clocksource: tsc-early: mask: 0xffffffffffffffff max_cycles: 0x33e452fbb2f, max_idle_ns: 440795236593 ns
May 31 16:09:57 tsybinSystem kernel: [    0.096020] Calibrating delay loop (skipped), value calculated using timer frequency.. 7200.00 BogoMIPS (lpj=14400000)
May 31 16:09:57 tsybinSystem kernel: [    0.096022] pid_max: default: 32768 minimum: 301
May 31 16:09:57 tsybinSystem kernel: [    0.096042] LSM: Security Framework initializing
May 31 16:09:57 tsybinSystem kernel: [    0.096049] Yama: becoming mindful.
May 31 16:09:57 tsybinSystem kernel: [    0.096071] AppArmor: AppArmor initialized
May 31 16:09:57 tsybinSystem kernel: [    0.096104] Mount-cache hash table entries: 16384 (order: 5, 131072 bytes, linear)
May 31 16:09:57 tsybinSystem kernel: [    0.096120] Mountpoint-cache hash table entries: 16384 (order: 5, 131072 bytes, linear)
May 31 16:09:57 tsybinSystem kernel: [    0.096226] *** VALIDATE proc ***
May 31 16:09:57 tsybinSystem kernel: [    0.096262] *** VALIDATE cgroup1 ***
May 31 16:09:57 tsybinSystem kernel: [    0.096263] *** VALIDATE cgroup2 ***
May 31 16:09:57 tsybinSystem kernel: [    0.096301] mce: CPU0: Thermal monitoring enabled (TM1)
May 31 16:09:57 tsybinSystem kernel: [    0.096316] process: using mwait in idle threads
May 31 16:09:57 tsybinSystem kernel: [    0.096317] Last level iTLB entries: 4KB 128, 2MB 8, 4MB 8
May 31 16:09:57 tsybinSystem kernel: [    0.096318] Last level dTLB entries: 4KB 64, 2MB 0, 4MB 0, 1GB 4
May 31 16:09:57 tsybinSystem kernel: [    0.096320] Spectre V1 : Mitigation: usercopy/swapgs barriers and __user pointer sanitization
May 31 16:09:57 tsybinSystem kernel: [    0.096320] Spectre V2 : Mitigation: Full generic retpoline
May 31 16:09:57 tsybinSystem kernel: [    0.096321] Spectre V2 : Spectre v2 / SpectreRSB mitigation: Filling RSB on context switch
May 31 16:09:57 tsybinSystem kernel: [    0.096321] Spectre V2 : Enabling Restricted Speculation for firmware calls
May 31 16:09:57 tsybinSystem kernel: [    0.096322] Spectre V2 : mitigation: Enabling conditional Indirect Branch Prediction Barrier
May 31 16:09:57 tsybinSystem kernel: [    0.096323] Speculative Store Bypass: Mitigation: Speculative Store Bypass disabled via prctl and seccomp
May 31 16:09:57 tsybinSystem kernel: [    0.096325] MDS: Mitigation: Clear CPU buffers
May 31 16:09:57 tsybinSystem kernel: [    0.096515] Freeing SMP alternatives memory: 36K
May 31 16:09:57 tsybinSystem kernel: [    0.098674] TSC deadline timer enabled
May 31 16:09:57 tsybinSystem kernel: [    0.098679] smpboot: CPU0: Intel(R) Core(TM) i3-8100 CPU @ 3.60GHz (family: 0x6, model: 0x9e, stepping: 0xb)
May 31 16:09:57 tsybinSystem kernel: [    0.098746] Performance Events: PEBS fmt3+, Skylake events, 32-deep LBR, full-width counters, Intel PMU driver.
May 31 16:09:57 tsybinSystem kernel: [    0.098750] ... version:                4
May 31 16:09:57 tsybinSystem kernel: [    0.098750] ... bit width:              48
May 31 16:09:57 tsybinSystem kernel: [    0.098750] ... generic registers:      8
May 31 16:09:57 tsybinSystem kernel: [    0.098751] ... value mask:             0000ffffffffffff
May 31 16:09:57 tsybinSystem kernel: [    0.098751] ... max period:             00007fffffffffff
May 31 16:09:57 tsybinSystem kernel: [    0.098752] ... fixed-purpose events:   3
May 31 16:09:57 tsybinSystem kernel: [    0.098752] ... event mask:             00000007000000ff
May 31 16:09:57 tsybinSystem kernel: [    0.098779] rcu: Hierarchical SRCU implementation.
May 31 16:09:57 tsybinSystem kernel: [    0.099376] NMI watchdog: Enabled. Permanently consumes one hw-PMU counter.
May 31 16:09:57 tsybinSystem kernel: [    0.099411] smp: Bringing up secondary CPUs ...
May 31 16:09:57 tsybinSystem kernel: [    0.099478] x86: Booting SMP configuration:
May 31 16:09:57 tsybinSystem kernel: [    0.099479] .... node  #0, CPUs:      #1 #2 #3
May 31 16:09:57 tsybinSystem kernel: [    0.101462] smp: Brought up 1 node, 4 CPUs
May 31 16:09:57 tsybinSystem kernel: [    0.101462] smpboot: Max logical packages: 1
May 31 16:09:57 tsybinSystem kernel: [    0.101462] smpboot: Total of 4 processors activated (28800.00 BogoMIPS)
May 31 16:09:57 tsybinSystem kernel: [    0.101462] devtmpfs: initialized
May 31 16:09:57 tsybinSystem kernel: [    0.101462] x86/mm: Memory block size: 128MB
May 31 16:09:57 tsybinSystem kernel: [    0.101462] PM: Registering ACPI NVS region [mem 0xb3e15000-0xb3e15fff] (4096 bytes)
May 31 16:09:57 tsybinSystem kernel: [    0.101462] PM: Registering ACPI NVS region [mem 0xc22fe000-0xc2625fff] (3309568 bytes)
May 31 16:09:57 tsybinSystem kernel: [    0.101462] clocksource: jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 7645041785100000 ns
May 31 16:09:57 tsybinSystem kernel: [    0.101462] futex hash table entries: 1024 (order: 4, 65536 bytes, linear)
May 31 16:09:57 tsybinSystem kernel: [    0.101462] pinctrl core: initialized pinctrl subsystem
May 31 16:09:57 tsybinSystem kernel: [    0.101462] PM: RTC time: 13:09:37, date: 2020-05-31
May 31 16:09:57 tsybinSystem kernel: [    0.101462] NET: Registered protocol family 16
May 31 16:09:57 tsybinSystem kernel: [    0.101462] audit: initializing netlink subsys (disabled)
May 31 16:09:57 tsybinSystem kernel: [    0.101462] audit: type=2000 audit(1590930577.028:1): state=initialized audit_enabled=0 res=1
May 31 16:09:57 tsybinSystem kernel: [    0.101462] EISA bus registered
May 31 16:09:57 tsybinSystem kernel: [    0.101462] cpuidle: using governor ladder
May 31 16:09:57 tsybinSystem kernel: [    0.101462] cpuidle: using governor menu
May 31 16:09:57 tsybinSystem kernel: [    0.101462] ACPI FADT declares the system doesn't support PCIe ASPM, so disable it
May 31 16:09:57 tsybinSystem kernel: [    0.101462] ACPI: bus type PCI registered
May 31 16:09:57 tsybinSystem kernel: [    0.101462] acpiphp: ACPI Hot Plug PCI Controller Driver version: 0.5
May 31 16:09:57 tsybinSystem kernel: [    0.101462] PCI: MMCONFIG for domain 0000 [bus 00-3f] at [mem 0xf8000000-0xfbffffff] (base 0xf8000000)
May 31 16:09:57 tsybinSystem kernel: [    0.101462] PCI: MMCONFIG at [mem 0xf8000000-0xfbffffff] reserved in E820
May 31 16:09:57 tsybinSystem kernel: [    0.101462] PCI: Using configuration type 1 for base access
May 31 16:09:57 tsybinSystem kernel: [    0.101462] ENERGY_PERF_BIAS: Set to 'normal', was 'performance'
May 31 16:09:57 tsybinSystem kernel: [    0.104850] HugeTLB registered 1.00 GiB page size, pre-allocated 0 pages
May 31 16:09:57 tsybinSystem kernel: [    0.104850] HugeTLB registered 2.00 MiB page size, pre-allocated 0 pages
May 31 16:09:57 tsybinSystem kernel: [    0.104850] ACPI: Added _OSI(Module Device)
May 31 16:09:57 tsybinSystem kernel: [    0.104850] ACPI: Added _OSI(Processor Device)
May 31 16:09:57 tsybinSystem kernel: [    0.104850] ACPI: Added _OSI(3.0 _SCP Extensions)
May 31 16:09:57 tsybinSystem kernel: [    0.104850] ACPI: Added _OSI(Processor Aggregator Device)
May 31 16:09:57 tsybinSystem kernel: [    0.104850] ACPI: Added _OSI(Linux-Dell-Video)
May 31 16:09:57 tsybinSystem kernel: [    0.104850] ACPI: Added _OSI(Linux-Lenovo-NV-HDMI-Audio)
May 31 16:09:57 tsybinSystem kernel: [    0.104850] ACPI: Added _OSI(Linux-HPI-Hybrid-Graphics)
May 31 16:09:57 tsybinSystem kernel: [    0.139478] ACPI: 12 ACPI AML tables successfully acquired and loaded
May 31 16:09:57 tsybinSystem kernel: [    0.147926] ACPI: Dynamic OEM Table Load:
May 31 16:09:57 tsybinSystem kernel: [    0.147930] ACPI: SSDT 0xFFFF9EC575546000 000738 (v02 PmRef  Cpu0Ist  00003000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.149223] ACPI: \_PR_.PR00: _OSC native thermal LVT Acked
May 31 16:09:57 tsybinSystem kernel: [    0.150602] ACPI: Dynamic OEM Table Load:
May 31 16:09:57 tsybinSystem kernel: [    0.150606] ACPI: SSDT 0xFFFF9EC57507BC00 0003FF (v02 PmRef  Cpu0Cst  00003001 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.151807] ACPI: Dynamic OEM Table Load:
May 31 16:09:57 tsybinSystem kernel: [    0.151809] ACPI: SSDT 0xFFFF9EC5757C0600 0000BA (v02 PmRef  Cpu0Hwp  00003000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.152942] ACPI: Dynamic OEM Table Load:
May 31 16:09:57 tsybinSystem kernel: [    0.152945] ACPI: SSDT 0xFFFF9EC575544800 000628 (v02 PmRef  HwpLvt   00003000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.154414] ACPI: Dynamic OEM Table Load:
May 31 16:09:57 tsybinSystem kernel: [    0.154420] ACPI: SSDT 0xFFFF9EC57541A000 000D14 (v02 PmRef  ApIst    00003000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.156218] ACPI: Dynamic OEM Table Load:
May 31 16:09:57 tsybinSystem kernel: [    0.156221] ACPI: SSDT 0xFFFF9EC57507A800 000317 (v02 PmRef  ApHwp    00003000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.157459] ACPI: Dynamic OEM Table Load:
May 31 16:09:57 tsybinSystem kernel: [    0.157462] ACPI: SSDT 0xFFFF9EC57507AC00 00030A (v02 PmRef  ApCst    00003000 INTL 20160422)
May 31 16:09:57 tsybinSystem kernel: [    0.161184] ACPI: Interpreter enabled
May 31 16:09:57 tsybinSystem kernel: [    0.161215] ACPI: (supports S0 S3 S4 S5)
May 31 16:09:57 tsybinSystem kernel: [    0.161216] ACPI: Using IOAPIC for interrupt routing
May 31 16:09:57 tsybinSystem kernel: [    0.161246] PCI: Using host bridge windows from ACPI; if necessary, use "pci=nocrs" and report a bug
May 31 16:09:57 tsybinSystem kernel: [    0.162319] ACPI: Enabled 6 GPEs in block 00 to 7F
May 31 16:09:57 tsybinSystem kernel: [    0.164897] ACPI: Power Resource [PG00] (on)
May 31 16:09:57 tsybinSystem kernel: [    0.165209] ACPI: Power Resource [PG01] (on)
May 31 16:09:57 tsybinSystem kernel: [    0.165516] ACPI: Power Resource [PG02] (on)
May 31 16:09:57 tsybinSystem kernel: [    0.187526] ACPI: Power Resource [FN00] (off)
May 31 16:09:57 tsybinSystem kernel: [    0.187604] ACPI: Power Resource [FN01] (off)
May 31 16:09:57 tsybinSystem kernel: [    0.187681] ACPI: Power Resource [FN02] (off)
May 31 16:09:57 tsybinSystem kernel: [    0.187757] ACPI: Power Resource [FN03] (off)
May 31 16:09:57 tsybinSystem kernel: [    0.187831] ACPI: Power Resource [FN04] (off)
May 31 16:09:57 tsybinSystem kernel: [    0.189261] ACPI: PCI Root Bridge [PCI0] (domain 0000 [bus 00-3e])
May 31 16:09:57 tsybinSystem kernel: [    0.189266] acpi PNP0A08:00: _OSC: OS supports [ExtendedConfig ASPM ClockPM Segments MSI HPX-Type3]
May 31 16:09:57 tsybinSystem kernel: [    0.189426] acpi PNP0A08:00: _OSC: platform does not support [PCIeHotplug SHPCHotplug PME]
May 31 16:09:57 tsybinSystem kernel: [    0.189575] acpi PNP0A08:00: _OSC: OS now controls [AER PCIeCapability LTR]
May 31 16:09:57 tsybinSystem kernel: [    0.189576] acpi PNP0A08:00: FADT indicates ASPM is unsupported, using BIOS configuration
May 31 16:09:57 tsybinSystem kernel: [    0.190521] PCI host bridge to bus 0000:00
May 31 16:09:57 tsybinSystem kernel: [    0.190522] pci_bus 0000:00: root bus resource [io  0x0000-0x0cf7 window]
May 31 16:09:57 tsybinSystem kernel: [    0.190523] pci_bus 0000:00: root bus resource [io  0x0d00-0xffff window]
May 31 16:09:57 tsybinSystem kernel: [    0.190524] pci_bus 0000:00: root bus resource [mem 0x000a0000-0x000bffff window]
May 31 16:09:57 tsybinSystem kernel: [    0.190525] pci_bus 0000:00: root bus resource [mem 0xc8000000-0xf7ffffff window]
May 31 16:09:57 tsybinSystem kernel: [    0.190525] pci_bus 0000:00: root bus resource [mem 0xfd000000-0xfe7fffff window]
May 31 16:09:57 tsybinSystem kernel: [    0.190526] pci_bus 0000:00: root bus resource [bus 00-3e]
May 31 16:09:57 tsybinSystem kernel: [    0.190533] pci 0000:00:00.0: [8086:3e1f] type 00 class 0x060000
May 31 16:09:57 tsybinSystem kernel: [    0.190826] pci 0000:00:01.0: [8086:1901] type 01 class 0x060400
May 31 16:09:57 tsybinSystem kernel: [    0.190861] pci 0000:00:01.0: PME# supported from D0 D3hot D3cold
May 31 16:09:57 tsybinSystem kernel: [    0.191028] pci 0000:00:02.0: [8086:3e91] type 00 class 0x030000
May 31 16:09:57 tsybinSystem kernel: [    0.191036] pci 0000:00:02.0: reg 0x10: [mem 0xf6000000-0xf6ffffff 64bit]
May 31 16:09:57 tsybinSystem kernel: [    0.191040] pci 0000:00:02.0: reg 0x18: [mem 0xe0000000-0xefffffff 64bit pref]
May 31 16:09:57 tsybinSystem kernel: [    0.191042] pci 0000:00:02.0: reg 0x20: [io  0xf000-0xf03f]
May 31 16:09:57 tsybinSystem kernel: [    0.191220] pci 0000:00:14.0: [8086:a2af] type 00 class 0x0c0330
May 31 16:09:57 tsybinSystem kernel: [    0.191240] pci 0000:00:14.0: reg 0x10: [mem 0xf7210000-0xf721ffff 64bit]
May 31 16:09:57 tsybinSystem kernel: [    0.191301] pci 0000:00:14.0: PME# supported from D3hot D3cold
May 31 16:09:57 tsybinSystem kernel: [    0.191515] pci 0000:00:16.0: [8086:a2ba] type 00 class 0x078000
May 31 16:09:57 tsybinSystem kernel: [    0.191554] pci 0000:00:16.0: reg 0x10: [mem 0xf722d000-0xf722dfff 64bit]
May 31 16:09:57 tsybinSystem kernel: [    0.191665] pci 0000:00:16.0: PME# supported from D3hot
May 31 16:09:57 tsybinSystem kernel: [    0.191859] pci 0000:00:17.0: [8086:a282] type 00 class 0x010601
May 31 16:09:57 tsybinSystem kernel: [    0.191875] pci 0000:00:17.0: reg 0x10: [mem 0xf7228000-0xf7229fff]
May 31 16:09:57 tsybinSystem kernel: [    0.191882] pci 0000:00:17.0: reg 0x14: [mem 0xf722c000-0xf722c0ff]
May 31 16:09:57 tsybinSystem kernel: [    0.191888] pci 0000:00:17.0: reg 0x18: [io  0xf090-0xf097]
May 31 16:09:57 tsybinSystem kernel: [    0.191894] pci 0000:00:17.0: reg 0x1c: [io  0xf080-0xf083]
May 31 16:09:57 tsybinSystem kernel: [    0.191900] pci 0000:00:17.0: reg 0x20: [io  0xf060-0xf07f]
May 31 16:09:57 tsybinSystem kernel: [    0.191907] pci 0000:00:17.0: reg 0x24: [mem 0xf722b000-0xf722b7ff]
May 31 16:09:57 tsybinSystem kernel: [    0.191944] pci 0000:00:17.0: PME# supported from D3hot
May 31 16:09:57 tsybinSystem kernel: [    0.192082] pci 0000:00:1c.0: [8086:a294] type 01 class 0x060400
May 31 16:09:57 tsybinSystem kernel: [    0.192149] pci 0000:00:1c.0: PME# supported from D0 D3hot D3cold
May 31 16:09:57 tsybinSystem kernel: [    0.192323] pci 0000:00:1c.7: [8086:a297] type 01 class 0x060400
May 31 16:09:57 tsybinSystem kernel: [    0.192391] pci 0000:00:1c.7: PME# supported from D0 D3hot D3cold
May 31 16:09:57 tsybinSystem kernel: [    0.192551] pci 0000:00:1d.0: [8086:a29a] type 01 class 0x060400
May 31 16:09:57 tsybinSystem kernel: [    0.192624] pci 0000:00:1d.0: PME# supported from D0 D3hot D3cold
May 31 16:09:57 tsybinSystem kernel: [    0.192803] pci 0000:00:1f.0: [8086:a2ca] type 00 class 0x060100
May 31 16:09:57 tsybinSystem kernel: [    0.193028] pci 0000:00:1f.2: [8086:a2a1] type 00 class 0x058000
May 31 16:09:57 tsybinSystem kernel: [    0.193042] pci 0000:00:1f.2: reg 0x10: [mem 0xf7224000-0xf7227fff]
May 31 16:09:57 tsybinSystem kernel: [    0.193212] pci 0000:00:1f.3: [8086:a2f0] type 00 class 0x040300
May 31 16:09:57 tsybinSystem kernel: [    0.193238] pci 0000:00:1f.3: reg 0x10: [mem 0xf7220000-0xf7223fff 64bit]
May 31 16:09:57 tsybinSystem kernel: [    0.193268] pci 0000:00:1f.3: reg 0x20: [mem 0xf7200000-0xf720ffff 64bit]
May 31 16:09:57 tsybinSystem kernel: [    0.193315] pci 0000:00:1f.3: PME# supported from D3hot D3cold
May 31 16:09:57 tsybinSystem kernel: [    0.193533] pci 0000:00:1f.4: [8086:a2a3] type 00 class 0x0c0500
May 31 16:09:57 tsybinSystem kernel: [    0.193593] pci 0000:00:1f.4: reg 0x10: [mem 0xf722a000-0xf722a0ff 64bit]
May 31 16:09:57 tsybinSystem kernel: [    0.193661] pci 0000:00:1f.4: reg 0x20: [io  0xf040-0xf05f]
May 31 16:09:57 tsybinSystem kernel: [    0.193888] pci 0000:01:00.0: [10ec:818b] type 00 class 0x028000
May 31 16:09:57 tsybinSystem kernel: [    0.193910] pci 0000:01:00.0: reg 0x10: [io  0xe000-0xe0ff]
May 31 16:09:57 tsybinSystem kernel: [    0.193930] pci 0000:01:00.0: reg 0x18: [mem 0xf7100000-0xf7103fff 64bit]
May 31 16:09:57 tsybinSystem kernel: [    0.194015] pci 0000:01:00.0: supports D1 D2
May 31 16:09:57 tsybinSystem kernel: [    0.194016] pci 0000:01:00.0: PME# supported from D0 D1 D2 D3hot D3cold
May 31 16:09:57 tsybinSystem kernel: [    0.194101] pci 0000:00:01.0: PCI bridge to [bus 01]
May 31 16:09:57 tsybinSystem kernel: [    0.194103] pci 0000:00:01.0:   bridge window [io  0xe000-0xefff]
May 31 16:09:57 tsybinSystem kernel: [    0.194104] pci 0000:00:01.0:   bridge window [mem 0xf7100000-0xf71fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.194142] pci 0000:00:1c.0: PCI bridge to [bus 02]
May 31 16:09:57 tsybinSystem kernel: [    0.194198] pci 0000:03:00.0: [10ec:8168] type 00 class 0x020000
May 31 16:09:57 tsybinSystem kernel: [    0.194225] pci 0000:03:00.0: reg 0x10: [io  0xd000-0xd0ff]
May 31 16:09:57 tsybinSystem kernel: [    0.194250] pci 0000:03:00.0: reg 0x18: [mem 0xf7004000-0xf7004fff 64bit]
May 31 16:09:57 tsybinSystem kernel: [    0.194265] pci 0000:03:00.0: reg 0x20: [mem 0xf7000000-0xf7003fff 64bit]
May 31 16:09:57 tsybinSystem kernel: [    0.194361] pci 0000:03:00.0: supports D1 D2
May 31 16:09:57 tsybinSystem kernel: [    0.194362] pci 0000:03:00.0: PME# supported from D0 D1 D2 D3hot D3cold
May 31 16:09:57 tsybinSystem kernel: [    0.194457] pci 0000:00:1c.7: PCI bridge to [bus 03]
May 31 16:09:57 tsybinSystem kernel: [    0.194459] pci 0000:00:1c.7:   bridge window [io  0xd000-0xdfff]
May 31 16:09:57 tsybinSystem kernel: [    0.194461] pci 0000:00:1c.7:   bridge window [mem 0xf7000000-0xf70fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.194501] pci 0000:00:1d.0: PCI bridge to [bus 04]
May 31 16:09:57 tsybinSystem kernel: [    0.195948] ACPI: PCI Interrupt Link [LNKA] (IRQs 3 4 5 6 10 *11 12 14 15)
May 31 16:09:57 tsybinSystem kernel: [    0.195997] ACPI: PCI Interrupt Link [LNKB] (IRQs 3 4 5 6 10 11 12 14 15) *0, disabled.
May 31 16:09:57 tsybinSystem kernel: [    0.196047] ACPI: PCI Interrupt Link [LNKC] (IRQs 3 4 5 6 10 11 12 14 *15)
May 31 16:09:57 tsybinSystem kernel: [    0.196095] ACPI: PCI Interrupt Link [LNKD] (IRQs 3 4 5 6 *10 11 12 14 15)
May 31 16:09:57 tsybinSystem kernel: [    0.196142] ACPI: PCI Interrupt Link [LNKE] (IRQs 3 4 5 6 10 11 12 14 15) *0, disabled.
May 31 16:09:57 tsybinSystem kernel: [    0.196190] ACPI: PCI Interrupt Link [LNKF] (IRQs 3 4 5 6 10 11 12 14 15) *0, disabled.
May 31 16:09:57 tsybinSystem kernel: [    0.196237] ACPI: PCI Interrupt Link [LNKG] (IRQs 3 4 5 6 10 11 12 14 15) *0, disabled.
May 31 16:09:57 tsybinSystem kernel: [    0.196284] ACPI: PCI Interrupt Link [LNKH] (IRQs 3 4 5 6 10 11 12 14 15) *0, disabled.
May 31 16:09:57 tsybinSystem kernel: [    0.196776] SCSI subsystem initialized
May 31 16:09:57 tsybinSystem kernel: [    0.196776] libata version 3.00 loaded.
May 31 16:09:57 tsybinSystem kernel: [    0.196776] pci 0000:00:02.0: vgaarb: setting as boot VGA device
May 31 16:09:57 tsybinSystem kernel: [    0.196776] pci 0000:00:02.0: vgaarb: VGA device added: decodes=io+mem,owns=io+mem,locks=none
May 31 16:09:57 tsybinSystem kernel: [    0.196776] pci 0000:00:02.0: vgaarb: bridge control possible
May 31 16:09:57 tsybinSystem kernel: [    0.196776] vgaarb: loaded
May 31 16:09:57 tsybinSystem kernel: [    0.196776] ACPI: bus type USB registered
May 31 16:09:57 tsybinSystem kernel: [    0.196776] usbcore: registered new interface driver usbfs
May 31 16:09:57 tsybinSystem kernel: [    0.196776] usbcore: registered new interface driver hub
May 31 16:09:57 tsybinSystem kernel: [    0.196776] usbcore: registered new device driver usb
May 31 16:09:57 tsybinSystem kernel: [    0.196776] pps_core: LinuxPPS API ver. 1 registered
May 31 16:09:57 tsybinSystem kernel: [    0.196776] pps_core: Software ver. 5.3.6 - Copyright 2005-2007 Rodolfo Giometti <giometti@linux.it>
May 31 16:09:57 tsybinSystem kernel: [    0.196776] PTP clock support registered
May 31 16:09:57 tsybinSystem kernel: [    0.196776] EDAC MC: Ver: 3.0.0
May 31 16:09:57 tsybinSystem kernel: [    0.196776] PCI: Using ACPI for IRQ routing
May 31 16:09:57 tsybinSystem kernel: [    0.203643] PCI: pci_cache_line_size set to 64 bytes
May 31 16:09:57 tsybinSystem kernel: [    0.203682] e820: reserve RAM buffer [mem 0x0009c400-0x0009ffff]
May 31 16:09:57 tsybinSystem kernel: [    0.203683] e820: reserve RAM buffer [mem 0xb23ca000-0xb3ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.203683] e820: reserve RAM buffer [mem 0xb3e15000-0xb3ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.203684] e820: reserve RAM buffer [mem 0xc0957000-0xc3ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.203685] e820: reserve RAM buffer [mem 0xc22fe000-0xc3ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.203685] e820: reserve RAM buffer [mem 0xc3000000-0xc3ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.203686] e820: reserve RAM buffer [mem 0x237000000-0x237ffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.203748] NetLabel: Initializing
May 31 16:09:57 tsybinSystem kernel: [    0.203748] NetLabel:  domain hash size = 128
May 31 16:09:57 tsybinSystem kernel: [    0.203749] NetLabel:  protocols = UNLABELED CIPSOv4 CALIPSO
May 31 16:09:57 tsybinSystem kernel: [    0.203758] NetLabel:  unlabeled traffic allowed by default
May 31 16:09:57 tsybinSystem kernel: [    0.204291] hpet0: at MMIO 0xfed00000, IRQs 2, 8, 0, 0, 0, 0, 0, 0
May 31 16:09:57 tsybinSystem kernel: [    0.204293] hpet0: 8 comparators, 64-bit 24.000000 MHz counter
May 31 16:09:57 tsybinSystem kernel: [    0.206331] clocksource: Switched to clocksource tsc-early
May 31 16:09:57 tsybinSystem kernel: [    0.209710] VFS: Disk quotas dquot_6.6.0
May 31 16:09:57 tsybinSystem kernel: [    0.212026] VFS: Dquot-cache hash table entries: 512 (order 0, 4096 bytes)
May 31 16:09:57 tsybinSystem kernel: [    0.212044] *** VALIDATE hugetlbfs ***
May 31 16:09:57 tsybinSystem kernel: [    0.212106] AppArmor: AppArmor Filesystem Enabled
May 31 16:09:57 tsybinSystem kernel: [    0.212127] pnp: PnP ACPI init
May 31 16:09:57 tsybinSystem kernel: [    0.212369] system 00:00: [io  0x0290-0x029f] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.212372] system 00:00: Plug and Play ACPI device, IDs PNP0c02 (active)
May 31 16:09:57 tsybinSystem kernel: [    0.212742] pnp 00:01: [dma 0 disabled]
May 31 16:09:57 tsybinSystem kernel: [    0.212852] pnp 00:01: Plug and Play ACPI device, IDs PNP0400 (active)
May 31 16:09:57 tsybinSystem kernel: [    0.213206] pnp 00:02: [dma 0 disabled]
May 31 16:09:57 tsybinSystem kernel: [    0.213230] pnp 00:02: Plug and Play ACPI device, IDs PNP0501 (active)
May 31 16:09:57 tsybinSystem kernel: [    0.213336] system 00:03: [io  0x0680-0x069f] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213337] system 00:03: [io  0xffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213337] system 00:03: [io  0xffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213338] system 00:03: [io  0xffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213339] system 00:03: [io  0x1800-0x18fe] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213340] system 00:03: [io  0x164e-0x164f] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213342] system 00:03: Plug and Play ACPI device, IDs PNP0c02 (active)
May 31 16:09:57 tsybinSystem kernel: [    0.213416] system 00:04: [io  0x0800-0x087f] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213418] system 00:04: Plug and Play ACPI device, IDs PNP0c02 (active)
May 31 16:09:57 tsybinSystem kernel: [    0.213430] pnp 00:05: Plug and Play ACPI device, IDs PNP0b00 (active)
May 31 16:09:57 tsybinSystem kernel: [    0.213458] system 00:06: [io  0x1854-0x1857] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213460] system 00:06: Plug and Play ACPI device, IDs INT3f0d PNP0c02 (active)
May 31 16:09:57 tsybinSystem kernel: [    0.213669] system 00:07: [mem 0xfed10000-0xfed17fff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213670] system 00:07: [mem 0xfed18000-0xfed18fff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213671] system 00:07: [mem 0xfed19000-0xfed19fff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213672] system 00:07: [mem 0xf8000000-0xfbffffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213672] system 00:07: [mem 0xfed20000-0xfed3ffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213673] system 00:07: [mem 0xfed90000-0xfed93fff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213674] system 00:07: [mem 0xfed45000-0xfed8ffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213675] system 00:07: [mem 0xff000000-0xffffffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213676] system 00:07: [mem 0xfee00000-0xfeefffff] could not be reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213677] system 00:07: [mem 0xf7fe0000-0xf7ffffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213679] system 00:07: Plug and Play ACPI device, IDs PNP0c02 (active)
May 31 16:09:57 tsybinSystem kernel: [    0.213709] system 00:08: [mem 0xfd000000-0xfdabffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213710] system 00:08: [mem 0xfdad0000-0xfdadffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213710] system 00:08: [mem 0xfdac0000-0xfdacffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213711] system 00:08: [mem 0xfdae0000-0xfdaeffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213713] system 00:08: [mem 0xfdaf0000-0xfdafffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213714] system 00:08: [mem 0xfdb00000-0xfdffffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213715] system 00:08: [mem 0xfe000000-0xfe01ffff] could not be reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213716] system 00:08: [mem 0xfe036000-0xfe03bfff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213716] system 00:08: [mem 0xfe03d000-0xfe3fffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213717] system 00:08: [mem 0xfe410000-0xfe7fffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213719] system 00:08: Plug and Play ACPI device, IDs PNP0c02 (active)
May 31 16:09:57 tsybinSystem kernel: [    0.213977] system 00:09: [io  0xfe00-0xfefe] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.213979] system 00:09: Plug and Play ACPI device, IDs PNP0c02 (active)
May 31 16:09:57 tsybinSystem kernel: [    0.215049] system 00:0a: [mem 0xfdaf0000-0xfdafffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.215050] system 00:0a: [mem 0xfdae0000-0xfdaeffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.215051] system 00:0a: [mem 0xfdac0000-0xfdacffff] has been reserved
May 31 16:09:57 tsybinSystem kernel: [    0.215053] system 00:0a: Plug and Play ACPI device, IDs PNP0c02 (active)
May 31 16:09:57 tsybinSystem kernel: [    0.215846] pnp: PnP ACPI: found 11 devices
May 31 16:09:57 tsybinSystem kernel: [    0.216614] thermal_sys: Registered thermal governor 'fair_share'
May 31 16:09:57 tsybinSystem kernel: [    0.216615] thermal_sys: Registered thermal governor 'bang_bang'
May 31 16:09:57 tsybinSystem kernel: [    0.216615] thermal_sys: Registered thermal governor 'step_wise'
May 31 16:09:57 tsybinSystem kernel: [    0.216616] thermal_sys: Registered thermal governor 'user_space'
May 31 16:09:57 tsybinSystem kernel: [    0.216616] thermal_sys: Registered thermal governor 'power_allocator'
May 31 16:09:57 tsybinSystem kernel: [    0.221104] clocksource: acpi_pm: mask: 0xffffff max_cycles: 0xffffff, max_idle_ns: 2085701024 ns
May 31 16:09:57 tsybinSystem kernel: [    0.221125] pci 0000:00:1c.0: bridge window [io  0x1000-0x0fff] to [bus 02] add_size 1000
May 31 16:09:57 tsybinSystem kernel: [    0.221127] pci 0000:00:1c.0: bridge window [mem 0x00100000-0x000fffff 64bit pref] to [bus 02] add_size 200000 add_align 100000
May 31 16:09:57 tsybinSystem kernel: [    0.221127] pci 0000:00:1c.0: bridge window [mem 0x00100000-0x000fffff] to [bus 02] add_size 200000 add_align 100000
May 31 16:09:57 tsybinSystem kernel: [    0.221129] pci 0000:00:1d.0: bridge window [io  0x1000-0x0fff] to [bus 04] add_size 1000
May 31 16:09:57 tsybinSystem kernel: [    0.221129] pci 0000:00:1d.0: bridge window [mem 0x00100000-0x000fffff 64bit pref] to [bus 04] add_size 200000 add_align 100000
May 31 16:09:57 tsybinSystem kernel: [    0.221130] pci 0000:00:1d.0: bridge window [mem 0x00100000-0x000fffff] to [bus 04] add_size 200000 add_align 100000
May 31 16:09:57 tsybinSystem kernel: [    0.221135] pci 0000:00:1c.0: BAR 14: assigned [mem 0xc8000000-0xc81fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.221138] pci 0000:00:1c.0: BAR 15: assigned [mem 0xc8200000-0xc83fffff 64bit pref]
May 31 16:09:57 tsybinSystem kernel: [    0.221139] pci 0000:00:1d.0: BAR 14: assigned [mem 0xc8400000-0xc85fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.221141] pci 0000:00:1d.0: BAR 15: assigned [mem 0xc8600000-0xc87fffff 64bit pref]
May 31 16:09:57 tsybinSystem kernel: [    0.221142] pci 0000:00:1c.0: BAR 13: assigned [io  0x2000-0x2fff]
May 31 16:09:57 tsybinSystem kernel: [    0.221144] pci 0000:00:1d.0: BAR 13: assigned [io  0x3000-0x3fff]
May 31 16:09:57 tsybinSystem kernel: [    0.221145] pci 0000:00:01.0: PCI bridge to [bus 01]
May 31 16:09:57 tsybinSystem kernel: [    0.221147] pci 0000:00:01.0:   bridge window [io  0xe000-0xefff]
May 31 16:09:57 tsybinSystem kernel: [    0.221148] pci 0000:00:01.0:   bridge window [mem 0xf7100000-0xf71fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.221152] pci 0000:00:1c.0: PCI bridge to [bus 02]
May 31 16:09:57 tsybinSystem kernel: [    0.221153] pci 0000:00:1c.0:   bridge window [io  0x2000-0x2fff]
May 31 16:09:57 tsybinSystem kernel: [    0.221155] pci 0000:00:1c.0:   bridge window [mem 0xc8000000-0xc81fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.221157] pci 0000:00:1c.0:   bridge window [mem 0xc8200000-0xc83fffff 64bit pref]
May 31 16:09:57 tsybinSystem kernel: [    0.221161] pci 0000:00:1c.7: PCI bridge to [bus 03]
May 31 16:09:57 tsybinSystem kernel: [    0.221162] pci 0000:00:1c.7:   bridge window [io  0xd000-0xdfff]
May 31 16:09:57 tsybinSystem kernel: [    0.221165] pci 0000:00:1c.7:   bridge window [mem 0xf7000000-0xf70fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.221169] pci 0000:00:1d.0: PCI bridge to [bus 04]
May 31 16:09:57 tsybinSystem kernel: [    0.221171] pci 0000:00:1d.0:   bridge window [io  0x3000-0x3fff]
May 31 16:09:57 tsybinSystem kernel: [    0.221174] pci 0000:00:1d.0:   bridge window [mem 0xc8400000-0xc85fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.221176] pci 0000:00:1d.0:   bridge window [mem 0xc8600000-0xc87fffff 64bit pref]
May 31 16:09:57 tsybinSystem kernel: [    0.221180] pci_bus 0000:00: resource 4 [io  0x0000-0x0cf7 window]
May 31 16:09:57 tsybinSystem kernel: [    0.221181] pci_bus 0000:00: resource 5 [io  0x0d00-0xffff window]
May 31 16:09:57 tsybinSystem kernel: [    0.221181] pci_bus 0000:00: resource 6 [mem 0x000a0000-0x000bffff window]
May 31 16:09:57 tsybinSystem kernel: [    0.221182] pci_bus 0000:00: resource 7 [mem 0xc8000000-0xf7ffffff window]
May 31 16:09:57 tsybinSystem kernel: [    0.221183] pci_bus 0000:00: resource 8 [mem 0xfd000000-0xfe7fffff window]
May 31 16:09:57 tsybinSystem kernel: [    0.221183] pci_bus 0000:01: resource 0 [io  0xe000-0xefff]
May 31 16:09:57 tsybinSystem kernel: [    0.221184] pci_bus 0000:01: resource 1 [mem 0xf7100000-0xf71fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.221185] pci_bus 0000:02: resource 0 [io  0x2000-0x2fff]
May 31 16:09:57 tsybinSystem kernel: [    0.221185] pci_bus 0000:02: resource 1 [mem 0xc8000000-0xc81fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.221186] pci_bus 0000:02: resource 2 [mem 0xc8200000-0xc83fffff 64bit pref]
May 31 16:09:57 tsybinSystem kernel: [    0.221187] pci_bus 0000:03: resource 0 [io  0xd000-0xdfff]
May 31 16:09:57 tsybinSystem kernel: [    0.221187] pci_bus 0000:03: resource 1 [mem 0xf7000000-0xf70fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.221188] pci_bus 0000:04: resource 0 [io  0x3000-0x3fff]
May 31 16:09:57 tsybinSystem kernel: [    0.221189] pci_bus 0000:04: resource 1 [mem 0xc8400000-0xc85fffff]
May 31 16:09:57 tsybinSystem kernel: [    0.221189] pci_bus 0000:04: resource 2 [mem 0xc8600000-0xc87fffff 64bit pref]
May 31 16:09:57 tsybinSystem kernel: [    0.221315] NET: Registered protocol family 2
May 31 16:09:57 tsybinSystem kernel: [    0.221406] tcp_listen_portaddr_hash hash table entries: 4096 (order: 4, 65536 bytes, linear)
May 31 16:09:57 tsybinSystem kernel: [    0.221440] TCP established hash table entries: 65536 (order: 7, 524288 bytes, linear)
May 31 16:09:57 tsybinSystem kernel: [    0.221536] TCP bind hash table entries: 65536 (order: 8, 1048576 bytes, linear)
May 31 16:09:57 tsybinSystem kernel: [    0.221587] TCP: Hash tables configured (established 65536 bind 65536)
May 31 16:09:57 tsybinSystem kernel: [    0.221610] UDP hash table entries: 4096 (order: 5, 131072 bytes, linear)
May 31 16:09:57 tsybinSystem kernel: [    0.221627] UDP-Lite hash table entries: 4096 (order: 5, 131072 bytes, linear)
May 31 16:09:57 tsybinSystem kernel: [    0.221676] NET: Registered protocol family 1
May 31 16:09:57 tsybinSystem kernel: [    0.221679] NET: Registered protocol family 44
May 31 16:09:57 tsybinSystem kernel: [    0.221687] pci 0000:00:02.0: Video device with shadowed ROM at [mem 0x000c0000-0x000dffff]
May 31 16:09:57 tsybinSystem kernel: [    0.221863] PCI: CLS 64 bytes, default 64
May 31 16:09:57 tsybinSystem kernel: [    0.221886] Trying to unpack rootfs image as initramfs...
May 31 16:09:57 tsybinSystem kernel: [    0.304158] Freeing initrd memory: 46780K
May 31 16:09:57 tsybinSystem kernel: [    0.304161] PCI-DMA: Using software bounce buffering for IO (SWIOTLB)
May 31 16:09:57 tsybinSystem kernel: [    0.304163] software IO TLB: mapped [mem 0xbc957000-0xc0957000] (64MB)
May 31 16:09:57 tsybinSystem kernel: [    0.304339] check: Scanning for low memory corruption every 60 seconds
May 31 16:09:57 tsybinSystem kernel: [    0.305661] Initialise system trusted keyrings
May 31 16:09:57 tsybinSystem kernel: [    0.305666] Key type blacklist registered
May 31 16:09:57 tsybinSystem kernel: [    0.305685] workingset: timestamp_bits=36 max_order=21 bucket_order=0
May 31 16:09:57 tsybinSystem kernel: [    0.306517] zbud: loaded
May 31 16:09:57 tsybinSystem kernel: [    0.306743] squashfs: version 4.0 (2009/01/31) Phillip Lougher
May 31 16:09:57 tsybinSystem kernel: [    0.306832] fuse: init (API version 7.31)
May 31 16:09:57 tsybinSystem kernel: [    0.306896] Platform Keyring initialized
May 31 16:09:57 tsybinSystem kernel: [    0.310001] Key type asymmetric registered
May 31 16:09:57 tsybinSystem kernel: [    0.310002] Asymmetric key parser 'x509' registered
May 31 16:09:57 tsybinSystem kernel: [    0.310009] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 244)
May 31 16:09:57 tsybinSystem kernel: [    0.310028] io scheduler mq-deadline registered
May 31 16:09:57 tsybinSystem kernel: [    0.310500] pcieport 0000:00:1c.7: AER: enabled with IRQ 122
May 31 16:09:57 tsybinSystem kernel: [    0.310658] shpchp: Standard Hot Plug PCI Controller Driver version: 0.4
May 31 16:09:57 tsybinSystem kernel: [    0.310700] vesafb: mode is 1680x1050x32, linelength=6720, pages=0
May 31 16:09:57 tsybinSystem kernel: [    0.310700] vesafb: scrolling: redraw
May 31 16:09:57 tsybinSystem kernel: [    0.310701] vesafb: Truecolor: size=8:8:8:8, shift=24:16:8:0
May 31 16:09:57 tsybinSystem kernel: [    0.310714] vesafb: framebuffer at 0xe0000000, mapped to 0x00000000cf99a3f9, using 6912k, total 6912k
May 31 16:09:57 tsybinSystem kernel: [    0.310737] fbcon: Deferring console take-over
May 31 16:09:57 tsybinSystem kernel: [    0.310738] fb0: VESA VGA frame buffer device
May 31 16:09:57 tsybinSystem kernel: [    0.310746] intel_idle: MWAIT substates: 0x11142120
May 31 16:09:57 tsybinSystem kernel: [    0.310746] intel_idle: v0.4.1 model 0x9E
May 31 16:09:57 tsybinSystem kernel: [    0.310948] intel_idle: lapic_timer_reliable_states 0xffffffff
May 31 16:09:57 tsybinSystem kernel: [    0.311067] input: Sleep Button as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0E:00/input/input0
May 31 16:09:57 tsybinSystem kernel: [    0.311073] ACPI: Sleep Button [SLPB]
May 31 16:09:57 tsybinSystem kernel: [    0.311092] input: Power Button as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0C:00/input/input1
May 31 16:09:57 tsybinSystem kernel: [    0.311095] ACPI: Power Button [PWRB]
May 31 16:09:57 tsybinSystem kernel: [    0.311114] input: Power Button as /devices/LNXSYSTM:00/LNXPWRBN:00/input/input2
May 31 16:09:57 tsybinSystem kernel: [    0.311156] ACPI: Power Button [PWRF]
May 31 16:09:57 tsybinSystem kernel: [    0.312149] thermal LNXTHERM:00: registered as thermal_zone0
May 31 16:09:57 tsybinSystem kernel: [    0.312150] ACPI: Thermal Zone [TZ00] (28 C)
May 31 16:09:57 tsybinSystem kernel: [    0.312277] thermal LNXTHERM:01: registered as thermal_zone1
May 31 16:09:57 tsybinSystem kernel: [    0.312278] ACPI: Thermal Zone [TZ01] (30 C)
May 31 16:09:57 tsybinSystem kernel: [    0.312420] Serial: 8250/16550 driver, 32 ports, IRQ sharing enabled
May 31 16:09:57 tsybinSystem kernel: [    0.333259] 00:02: ttyS0 at I/O 0x3f8 (irq = 4, base_baud = 115200) is a 16550A
May 31 16:09:57 tsybinSystem kernel: [    0.334644] Linux agpgart interface v0.103
May 31 16:09:57 tsybinSystem kernel: [    0.335899] loop: module loaded
May 31 16:09:57 tsybinSystem kernel: [    0.336010] libphy: Fixed MDIO Bus: probed
May 31 16:09:57 tsybinSystem kernel: [    0.336010] tun: Universal TUN/TAP device driver, 1.6
May 31 16:09:57 tsybinSystem kernel: [    0.336027] PPP generic driver version 2.4.2
May 31 16:09:57 tsybinSystem kernel: [    0.336047] ehci_hcd: USB 2.0 'Enhanced' Host Controller (EHCI) Driver
May 31 16:09:57 tsybinSystem kernel: [    0.336049] ehci-pci: EHCI PCI platform driver
May 31 16:09:57 tsybinSystem kernel: [    0.336054] ehci-platform: EHCI generic platform driver
May 31 16:09:57 tsybinSystem kernel: [    0.336059] ohci_hcd: USB 1.1 'Open' Host Controller (OHCI) Driver
May 31 16:09:57 tsybinSystem kernel: [    0.336060] ohci-pci: OHCI PCI platform driver
May 31 16:09:57 tsybinSystem kernel: [    0.336065] ohci-platform: OHCI generic platform driver
May 31 16:09:57 tsybinSystem kernel: [    0.336069] uhci_hcd: USB Universal Host Controller Interface driver
May 31 16:09:57 tsybinSystem kernel: [    0.336177] xhci_hcd 0000:00:14.0: xHCI Host Controller
May 31 16:09:57 tsybinSystem kernel: [    0.336180] xhci_hcd 0000:00:14.0: new USB bus registered, assigned bus number 1
May 31 16:09:57 tsybinSystem kernel: [    0.337244] xhci_hcd 0000:00:14.0: hcc params 0x200077c1 hci version 0x100 quirks 0x0000000000009810
May 31 16:09:57 tsybinSystem kernel: [    0.337249] xhci_hcd 0000:00:14.0: cache line size of 64 is not supported
May 31 16:09:57 tsybinSystem kernel: [    0.337379] usb usb1: New USB device found, idVendor=1d6b, idProduct=0002, bcdDevice= 5.03
May 31 16:09:57 tsybinSystem kernel: [    0.337380] usb usb1: New USB device strings: Mfr=3, Product=2, SerialNumber=1
May 31 16:09:57 tsybinSystem kernel: [    0.337381] usb usb1: Product: xHCI Host Controller
May 31 16:09:57 tsybinSystem kernel: [    0.337382] usb usb1: Manufacturer: Linux 5.3.0-51-generic xhci-hcd
May 31 16:09:57 tsybinSystem kernel: [    0.337382] usb usb1: SerialNumber: 0000:00:14.0
May 31 16:09:57 tsybinSystem kernel: [    0.337459] hub 1-0:1.0: USB hub found
May 31 16:09:57 tsybinSystem kernel: [    0.337470] hub 1-0:1.0: 10 ports detected
May 31 16:09:57 tsybinSystem kernel: [    0.338489] xhci_hcd 0000:00:14.0: xHCI Host Controller
May 31 16:09:57 tsybinSystem kernel: [    0.338491] xhci_hcd 0000:00:14.0: new USB bus registered, assigned bus number 2
May 31 16:09:57 tsybinSystem kernel: [    0.338494] xhci_hcd 0000:00:14.0: Host supports USB 3.0 SuperSpeed
May 31 16:09:57 tsybinSystem kernel: [    0.338516] usb usb2: New USB device found, idVendor=1d6b, idProduct=0003, bcdDevice= 5.03
May 31 16:09:57 tsybinSystem kernel: [    0.338516] usb usb2: New USB device strings: Mfr=3, Product=2, SerialNumber=1
May 31 16:09:57 tsybinSystem kernel: [    0.338517] usb usb2: Product: xHCI Host Controller
May 31 16:09:57 tsybinSystem kernel: [    0.338518] usb usb2: Manufacturer: Linux 5.3.0-51-generic xhci-hcd
May 31 16:09:57 tsybinSystem kernel: [    0.338518] usb usb2: SerialNumber: 0000:00:14.0
May 31 16:09:57 tsybinSystem kernel: [    0.338591] hub 2-0:1.0: USB hub found
May 31 16:09:57 tsybinSystem kernel: [    0.338598] hub 2-0:1.0: 4 ports detected
May 31 16:09:57 tsybinSystem kernel: [    0.339033] i8042: PNP: No PS/2 controller found.
May 31 16:09:57 tsybinSystem kernel: [    0.339122] mousedev: PS/2 mouse device common for all mice
May 31 16:09:57 tsybinSystem kernel: [    0.339324] rtc_cmos 00:05: RTC can wake from S4
May 31 16:09:57 tsybinSystem kernel: [    0.339793] rtc_cmos 00:05: registered as rtc0
May 31 16:09:57 tsybinSystem kernel: [    0.339801] rtc_cmos 00:05: alarms up to one month, y3k, 242 bytes nvram, hpet irqs
May 31 16:09:57 tsybinSystem kernel: [    0.339804] i2c /dev entries driver
May 31 16:09:57 tsybinSystem kernel: [    0.339831] device-mapper: uevent: version 1.0.3
May 31 16:09:57 tsybinSystem kernel: [    0.339862] device-mapper: ioctl: 4.40.0-ioctl (2019-01-18) initialised: dm-devel@redhat.com
May 31 16:09:57 tsybinSystem kernel: [    0.339874] platform eisa.0: Probing EISA bus 0
May 31 16:09:57 tsybinSystem kernel: [    0.339874] platform eisa.0: EISA: Cannot allocate resource for mainboard
May 31 16:09:57 tsybinSystem kernel: [    0.339875] platform eisa.0: Cannot allocate resource for EISA slot 1
May 31 16:09:57 tsybinSystem kernel: [    0.339876] platform eisa.0: Cannot allocate resource for EISA slot 2
May 31 16:09:57 tsybinSystem kernel: [    0.339876] platform eisa.0: Cannot allocate resource for EISA slot 3
May 31 16:09:57 tsybinSystem kernel: [    0.339877] platform eisa.0: Cannot allocate resource for EISA slot 4
May 31 16:09:57 tsybinSystem kernel: [    0.339878] platform eisa.0: Cannot allocate resource for EISA slot 5
May 31 16:09:57 tsybinSystem kernel: [    0.339878] platform eisa.0: Cannot allocate resource for EISA slot 6
May 31 16:09:57 tsybinSystem kernel: [    0.339879] platform eisa.0: Cannot allocate resource for EISA slot 7
May 31 16:09:57 tsybinSystem kernel: [    0.339879] platform eisa.0: Cannot allocate resource for EISA slot 8
May 31 16:09:57 tsybinSystem kernel: [    0.339880] platform eisa.0: EISA: Detected 0 cards
May 31 16:09:57 tsybinSystem kernel: [    0.339882] intel_pstate: Intel P-state driver initializing
May 31 16:09:57 tsybinSystem kernel: [    0.340110] intel_pstate: HWP enabled
May 31 16:09:57 tsybinSystem kernel: [    0.340159] ledtrig-cpu: registered to indicate activity on CPUs
May 31 16:09:57 tsybinSystem kernel: [    0.340177] resource sanity check: requesting [mem 0xfdffe800-0xfe0007ff], which spans more than pnp 00:08 [mem 0xfdb00000-0xfdffffff]
May 31 16:09:57 tsybinSystem kernel: [    0.340180] caller pmc_core_probe+0x7f/0x17f mapping multiple BARs
May 31 16:09:57 tsybinSystem kernel: [    0.340188] intel_pmc_core INT33A1:00:  initialized
May 31 16:09:57 tsybinSystem kernel: [    0.340338] NET: Registered protocol family 10
May 31 16:09:57 tsybinSystem kernel: [    0.346799] Segment Routing with IPv6
May 31 16:09:57 tsybinSystem kernel: [    0.346815] NET: Registered protocol family 17
May 31 16:09:57 tsybinSystem kernel: [    0.346885] Key type dns_resolver registered
May 31 16:09:57 tsybinSystem kernel: [    0.347181] RAS: Correctable Errors collector initialized.
May 31 16:09:57 tsybinSystem kernel: [    0.347205] microcode: sig=0x906eb, pf=0x2, revision=0xca
May 31 16:09:57 tsybinSystem kernel: [    0.347321] microcode: Microcode Update Driver: v2.2.
May 31 16:09:57 tsybinSystem kernel: [    0.347327] sched_clock: Marking stable (346967297, 351213)->(352452229, -5133719)
May 31 16:09:57 tsybinSystem kernel: [    0.347486] registered taskstats version 1
May 31 16:09:57 tsybinSystem kernel: [    0.347491] Loading compiled-in X.509 certificates
May 31 16:09:57 tsybinSystem kernel: [    0.348911] Loaded X.509 cert 'Build time autogenerated kernel key: 185a54966a4f9839404817dc04abbc687b113093'
May 31 16:09:57 tsybinSystem kernel: [    0.348927] zswap: loaded using pool lzo/zbud
May 31 16:09:57 tsybinSystem kernel: [    0.354893] Key type big_key registered
May 31 16:09:57 tsybinSystem kernel: [    0.357897] Key type encrypted registered
May 31 16:09:57 tsybinSystem kernel: [    0.357900] AppArmor: AppArmor sha1 policy hashing enabled
May 31 16:09:57 tsybinSystem kernel: [    0.357909] ima: No TPM chip found, activating TPM-bypass!
May 31 16:09:57 tsybinSystem kernel: [    0.357914] ima: Allocated hash algorithm: sha1
May 31 16:09:57 tsybinSystem kernel: [    0.357918] No architecture policies found
May 31 16:09:57 tsybinSystem kernel: [    0.357924] evm: Initialising EVM extended attributes:
May 31 16:09:57 tsybinSystem kernel: [    0.357924] evm: security.selinux
May 31 16:09:57 tsybinSystem kernel: [    0.357925] evm: security.SMACK64
May 31 16:09:57 tsybinSystem kernel: [    0.357925] evm: security.SMACK64EXEC
May 31 16:09:57 tsybinSystem kernel: [    0.357925] evm: security.SMACK64TRANSMUTE
May 31 16:09:57 tsybinSystem kernel: [    0.357926] evm: security.SMACK64MMAP
May 31 16:09:57 tsybinSystem kernel: [    0.357926] evm: security.apparmor
May 31 16:09:57 tsybinSystem kernel: [    0.357926] evm: security.ima
May 31 16:09:57 tsybinSystem kernel: [    0.357926] evm: security.capability
May 31 16:09:57 tsybinSystem kernel: [    0.357927] evm: HMAC attrs: 0x1
May 31 16:09:57 tsybinSystem kernel: [    0.358852] PM:   Magic number: 4:319:181
May 31 16:09:57 tsybinSystem kernel: [    0.358900] acpi device:40: hash matches
May 31 16:09:57 tsybinSystem kernel: [    0.359047] rtc_cmos 00:05: setting system clock to 2020-05-31T13:09:38 UTC (1590930578)
May 31 16:09:57 tsybinSystem kernel: [    0.359944] Freeing unused decrypted memory: 2040K
May 31 16:09:57 tsybinSystem kernel: [    0.360184] Freeing unused kernel image memory: 2676K
May 31 16:09:57 tsybinSystem kernel: [    0.384121] Write protecting the kernel read-only data: 22528k
May 31 16:09:57 tsybinSystem kernel: [    0.384521] Freeing unused kernel image memory: 2008K
May 31 16:09:57 tsybinSystem kernel: [    0.384705] Freeing unused kernel image memory: 1416K
May 31 16:09:57 tsybinSystem kernel: [    0.391983] x86/mm: Checked W+X mappings: passed, no W+X pages found.
May 31 16:09:57 tsybinSystem kernel: [    0.391983] x86/mm: Checking user space page tables
May 31 16:09:57 tsybinSystem kernel: [    0.399124] x86/mm: Checked W+X mappings: passed, no W+X pages found.
May 31 16:09:57 tsybinSystem kernel: [    0.399125] Run /init as init process
May 31 16:09:57 tsybinSystem kernel: [    0.463888] ahci 0000:00:17.0: version 3.0
May 31 16:09:57 tsybinSystem kernel: [    0.464073] ahci 0000:00:17.0: AHCI 0001.0301 32 slots 4 ports 6 Gbps 0xf impl SATA mode
May 31 16:09:57 tsybinSystem kernel: [    0.464074] ahci 0000:00:17.0: flags: 64bit ncq sntf led clo only pio slum part ems deso sadm sds apst 
May 31 16:09:57 tsybinSystem kernel: [    0.464585] r8169 0000:03:00.0: can't disable ASPM; OS doesn't have ASPM control
May 31 16:09:57 tsybinSystem kernel: [    0.465628] i801_smbus 0000:00:1f.4: SPD Write Disable is set
May 31 16:09:57 tsybinSystem kernel: [    0.465657] i801_smbus 0000:00:1f.4: SMBus using PCI interrupt
May 31 16:09:57 tsybinSystem kernel: [    0.477318] libphy: r8169: probed
May 31 16:09:57 tsybinSystem kernel: [    0.477455] r8169 0000:03:00.0 eth0: RTL8168h/8111h, a8:5e:45:2f:1e:67, XID 541, IRQ 126
May 31 16:09:57 tsybinSystem kernel: [    0.477456] r8169 0000:03:00.0 eth0: jumbo features [frames: 9200 bytes, tx checksumming: ko]
May 31 16:09:57 tsybinSystem kernel: [    0.496982] r8169 0000:03:00.0 enp3s0: renamed from eth0
May 31 16:09:57 tsybinSystem kernel: [    0.500534] scsi host0: ahci
May 31 16:09:57 tsybinSystem kernel: [    0.500734] scsi host1: ahci
May 31 16:09:57 tsybinSystem kernel: [    0.500832] scsi host2: ahci
May 31 16:09:57 tsybinSystem kernel: [    0.500936] scsi host3: ahci
May 31 16:09:57 tsybinSystem kernel: [    0.500968] ata1: SATA max UDMA/133 abar m2048@0xf722b000 port 0xf722b100 irq 125
May 31 16:09:57 tsybinSystem kernel: [    0.500969] ata2: SATA max UDMA/133 abar m2048@0xf722b000 port 0xf722b180 irq 125
May 31 16:09:57 tsybinSystem kernel: [    0.500971] ata3: SATA max UDMA/133 abar m2048@0xf722b000 port 0xf722b200 irq 125
May 31 16:09:57 tsybinSystem kernel: [    0.500972] ata4: SATA max UDMA/133 abar m2048@0xf722b000 port 0xf722b280 irq 125
May 31 16:09:57 tsybinSystem kernel: [    0.672134] usb 1-1: new full-speed USB device number 2 using xhci_hcd
May 31 16:09:57 tsybinSystem kernel: [    0.816138] ata3: SATA link down (SStatus 4 SControl 300)
May 31 16:09:57 tsybinSystem kernel: [    0.820137] ata1: SATA link up 6.0 Gbps (SStatus 133 SControl 300)
May 31 16:09:57 tsybinSystem kernel: [    0.820150] ata4: SATA link down (SStatus 4 SControl 300)
May 31 16:09:57 tsybinSystem kernel: [    0.820165] ata2: SATA link down (SStatus 4 SControl 300)
May 31 16:09:57 tsybinSystem kernel: [    0.823888] ata1.00: ACPI cmd ef/10:06:00:00:00:00 (SET FEATURES) succeeded
May 31 16:09:57 tsybinSystem kernel: [    0.823889] ata1.00: ACPI cmd f5/00:00:00:00:00:00 (SECURITY FREEZE LOCK) filtered out
May 31 16:09:57 tsybinSystem kernel: [    0.823890] ata1.00: ACPI cmd b1/c1:00:00:00:00:00 (DEVICE CONFIGURATION OVERLAY) filtered out
May 31 16:09:57 tsybinSystem kernel: [    0.823901] usb 1-1: New USB device found, idVendor=0a5c, idProduct=218c, bcdDevice= 3.19
May 31 16:09:57 tsybinSystem kernel: [    0.823902] usb 1-1: New USB device strings: Mfr=1, Product=2, SerialNumber=3
May 31 16:09:57 tsybinSystem kernel: [    0.823903] usb 1-1: Product: Broadcom Bluetooth 3.0 Dongle
May 31 16:09:57 tsybinSystem kernel: [    0.823903] usb 1-1: Manufacturer: Broadcom Corp
May 31 16:09:57 tsybinSystem kernel: [    0.823904] usb 1-1: SerialNumber: 00198600399C
May 31 16:09:57 tsybinSystem kernel: [    0.824564] ata1.00: ATA-10: WDC WDS240G2G0A-00JH30, UF220400, max UDMA/133
May 31 16:09:57 tsybinSystem kernel: [    0.824565] ata1.00: 468862128 sectors, multi 1: LBA48 NCQ (depth 32)
May 31 16:09:57 tsybinSystem kernel: [    0.832125] ata1.00: ACPI cmd ef/10:06:00:00:00:00 (SET FEATURES) succeeded
May 31 16:09:57 tsybinSystem kernel: [    0.832126] ata1.00: ACPI cmd f5/00:00:00:00:00:00 (SECURITY FREEZE LOCK) filtered out
May 31 16:09:57 tsybinSystem kernel: [    0.832127] ata1.00: ACPI cmd b1/c1:00:00:00:00:00 (DEVICE CONFIGURATION OVERLAY) filtered out
May 31 16:09:57 tsybinSystem kernel: [    0.833289] ata1.00: configured for UDMA/133
May 31 16:09:57 tsybinSystem kernel: [    0.833463] scsi 0:0:0:0: Direct-Access     ATA      WDC WDS240G2G0A- 0400 PQ: 0 ANSI: 5
May 31 16:09:57 tsybinSystem kernel: [    0.833701] sd 0:0:0:0: Attached scsi generic sg0 type 0
May 31 16:09:57 tsybinSystem kernel: [    0.833706] sd 0:0:0:0: [sda] 468862128 512-byte logical blocks: (240 GB/224 GiB)
May 31 16:09:57 tsybinSystem kernel: [    0.833711] sd 0:0:0:0: [sda] Write Protect is off
May 31 16:09:57 tsybinSystem kernel: [    0.833712] sd 0:0:0:0: [sda] Mode Sense: 00 3a 00 00
May 31 16:09:57 tsybinSystem kernel: [    0.833718] sd 0:0:0:0: [sda] Write cache: enabled, read cache: enabled, doesn't support DPO or FUA
May 31 16:09:57 tsybinSystem kernel: [    0.838506]  sda: sda1 sda2 sda3 sda4
May 31 16:09:57 tsybinSystem kernel: [    0.839117] sd 0:0:0:0: [sda] Attached SCSI disk
May 31 16:09:57 tsybinSystem kernel: [    0.952137] usb 1-4: new high-speed USB device number 3 using xhci_hcd
May 31 16:09:57 tsybinSystem kernel: [    0.973558] usb 1-4: New USB device found, idVendor=03f0, idProduct=4117, bcdDevice= 1.00
May 31 16:09:57 tsybinSystem kernel: [    0.973559] usb 1-4: New USB device strings: Mfr=1, Product=2, SerialNumber=3
May 31 16:09:57 tsybinSystem kernel: [    0.973560] usb 1-4: Product: HP LaserJet 1018
May 31 16:09:57 tsybinSystem kernel: [    0.973561] usb 1-4: Manufacturer: Hewlett-Packard
May 31 16:09:57 tsybinSystem kernel: [    0.973561] usb 1-4: SerialNumber: KP2YJZP
May 31 16:09:57 tsybinSystem kernel: [    1.100131] usb 1-5: new low-speed USB device number 4 using xhci_hcd
May 31 16:09:57 tsybinSystem kernel: [    1.252029] usb 1-5: New USB device found, idVendor=046d, idProduct=c077, bcdDevice=72.00
May 31 16:09:57 tsybinSystem kernel: [    1.252030] usb 1-5: New USB device strings: Mfr=1, Product=2, SerialNumber=0
May 31 16:09:57 tsybinSystem kernel: [    1.252030] usb 1-5: Product: USB Optical Mouse
May 31 16:09:57 tsybinSystem kernel: [    1.252031] usb 1-5: Manufacturer: Logitech
May 31 16:09:57 tsybinSystem kernel: [    1.320130] tsc: Refined TSC clocksource calibration: 3599.999 MHz
May 31 16:09:57 tsybinSystem kernel: [    1.320133] clocksource: tsc: mask: 0xffffffffffffffff max_cycles: 0x33e4525366a, max_idle_ns: 440795257657 ns
May 31 16:09:57 tsybinSystem kernel: [    1.320168] clocksource: Switched to clocksource tsc
May 31 16:09:57 tsybinSystem kernel: [    1.380125] usb 1-6: new low-speed USB device number 5 using xhci_hcd
May 31 16:09:57 tsybinSystem kernel: [    1.533658] usb 1-6: New USB device found, idVendor=04f3, idProduct=0103, bcdDevice= 1.07
May 31 16:09:57 tsybinSystem kernel: [    1.533659] usb 1-6: New USB device strings: Mfr=0, Product=0, SerialNumber=0
May 31 16:09:57 tsybinSystem kernel: [    1.537506] hidraw: raw HID events driver (C) Jiri Kosina
May 31 16:09:57 tsybinSystem kernel: [    1.546083] usbcore: registered new interface driver usbhid
May 31 16:09:57 tsybinSystem kernel: [    1.546084] usbhid: USB HID core driver
May 31 16:09:57 tsybinSystem kernel: [    1.547444] input: Logitech USB Optical Mouse as /devices/pci0000:00/0000:00:14.0/usb1/1-5/1-5:1.0/0003:046D:C077.0001/input/input3
May 31 16:09:57 tsybinSystem kernel: [    1.547614] hid-generic 0003:046D:C077.0001: input,hidraw0: USB HID v1.11 Mouse [Logitech USB Optical Mouse] on usb-0000:00:14.0-5/input0
May 31 16:09:57 tsybinSystem kernel: [    1.547681] input: HID 04f3:0103 as /devices/pci0000:00/0000:00:14.0/usb1/1-6/1-6:1.0/0003:04F3:0103.0002/input/input4
May 31 16:09:57 tsybinSystem kernel: [    1.547711] hid-generic 0003:04F3:0103.0002: input,hidraw1: USB HID v1.11 Keyboard [HID 04f3:0103] on usb-0000:00:14.0-6/input0
May 31 16:09:57 tsybinSystem kernel: [    1.547800] input: HID 04f3:0103 Consumer Control as /devices/pci0000:00/0000:00:14.0/usb1/1-6/1-6:1.1/0003:04F3:0103.0003/input/input5
May 31 16:09:57 tsybinSystem kernel: [    1.547826] input: HID 04f3:0103 System Control as /devices/pci0000:00/0000:00:14.0/usb1/1-6/1-6:1.1/0003:04F3:0103.0003/input/input6
May 31 16:09:57 tsybinSystem kernel: [    1.547851] hid-generic 0003:04F3:0103.0003: input,hidraw2: USB HID v1.11 Device [HID 04f3:0103] on usb-0000:00:14.0-6/input1
May 31 16:09:57 tsybinSystem kernel: [    1.601759] fbcon: Taking over console
May 31 16:09:57 tsybinSystem kernel: [    1.601810] Console: switching to colour frame buffer device 210x65
May 31 16:09:57 tsybinSystem kernel: [    1.611920] EXT4-fs (sda1): mounted filesystem with ordered data mode. Opts: (null)
May 31 16:09:57 tsybinSystem kernel: [    2.524656] EXT4-fs (sda1): re-mounted. Opts: errors=remount-ro
May 31 16:09:57 tsybinSystem kernel: [    2.553900] lp: driver loaded but no devices found
May 31 16:09:57 tsybinSystem kernel: [    2.558571] ppdev: user-space parallel port driver
May 31 16:09:57 tsybinSystem kernel: [    2.563869] parport_pc 00:01: reported by Plug and Play ACPI
May 31 16:09:57 tsybinSystem kernel: [    2.563954] parport0: PC-style at 0x378, irq 5 [PCSPP]
May 31 16:09:57 tsybinSystem kernel: [    2.660210] lp0: using parport0 (interrupt-driven).
May 31 16:09:57 tsybinSystem kernel: [    2.676322] mc: Linux media interface: v0.10
May 31 16:09:57 tsybinSystem kernel: [    2.689734] videodev: Linux video capture interface: v2.00
May 31 16:09:57 tsybinSystem kernel: [    2.695906] v4l2loopback_dc: loading out-of-tree module taints kernel.
May 31 16:09:57 tsybinSystem kernel: [    2.695921] v4l2loopback_dc: module verification failed: signature and/or required key missing - tainting kernel
May 31 16:09:57 tsybinSystem kernel: [    2.696214] v4l2loopback driver version 0.6.3 (droidcam) loaded
May 31 16:09:57 tsybinSystem kernel: [    2.982939] RAPL PMU: API unit is 2^-32 Joules, 4 fixed counters, 655360 ms ovfl timer
May 31 16:09:57 tsybinSystem kernel: [    2.982940] RAPL PMU: hw unit of domain pp0-core 2^-14 Joules
May 31 16:09:57 tsybinSystem kernel: [    2.982940] RAPL PMU: hw unit of domain package 2^-14 Joules
May 31 16:09:57 tsybinSystem kernel: [    2.982940] RAPL PMU: hw unit of domain dram 2^-14 Joules
May 31 16:09:57 tsybinSystem kernel: [    2.982941] RAPL PMU: hw unit of domain pp1-gpu 2^-14 Joules
May 31 16:09:57 tsybinSystem kernel: [    2.989106] asus_wmi: ASUS WMI generic driver loaded
May 31 16:09:57 tsybinSystem kernel: [    2.996888] mei_me 0000:00:16.0: enabling device (0004 -> 0006)
May 31 16:09:57 tsybinSystem kernel: [    2.999095] asus_wmi: Initialization: 0x0
May 31 16:09:57 tsybinSystem kernel: [    2.999120] asus_wmi: BIOS WMI version: 0.9
May 31 16:09:57 tsybinSystem kernel: [    2.999243] asus_wmi: SFUN value: 0x0
May 31 16:09:57 tsybinSystem kernel: [    2.999245] eeepc-wmi eeepc-wmi: Detected ASUSWMI, use DCTS
May 31 16:09:57 tsybinSystem kernel: [    2.999609] input: Eee PC WMI hotkeys as /devices/platform/eeepc-wmi/input/input7
May 31 16:09:57 tsybinSystem kernel: [    2.999780] asus_wmi: Number of fans: 1
May 31 16:09:57 tsybinSystem kernel: [    3.092630] cfg80211: Loading compiled-in X.509 certificates for regulatory database
May 31 16:09:57 tsybinSystem kernel: [    3.099258] cryptd: max_cpu_qlen set to 1000
May 31 16:09:57 tsybinSystem kernel: [    3.111101] cfg80211: Loaded X.509 cert 'sforshee: 00b28ddf47aef9cea7'
May 31 16:09:57 tsybinSystem kernel: [    3.190980] AVX2 version of gcm_enc/dec engaged.
May 31 16:09:57 tsybinSystem kernel: [    3.190980] AES CTR mode by8 optimization enabled
May 31 16:09:57 tsybinSystem kernel: [    3.377733] Bluetooth: Core ver 2.22
May 31 16:09:57 tsybinSystem kernel: [    3.377745] NET: Registered protocol family 31
May 31 16:09:57 tsybinSystem kernel: [    3.377746] Bluetooth: HCI device and connection manager initialized
May 31 16:09:57 tsybinSystem kernel: [    3.377749] Bluetooth: HCI socket layer initialized
May 31 16:09:57 tsybinSystem kernel: [    3.377750] Bluetooth: L2CAP socket layer initialized
May 31 16:09:57 tsybinSystem kernel: [    3.377751] Bluetooth: SCO socket layer initialized
May 31 16:09:57 tsybinSystem kernel: [    4.368547] checking generic (e0000000 6c0000) vs hw (e0000000 10000000)
May 31 16:09:57 tsybinSystem kernel: [    4.368548] fb0: switching to inteldrmfb from VESA VGA
May 31 16:09:57 tsybinSystem kernel: [    4.368609] Console: switching to colour dummy device 80x25
May 31 16:09:57 tsybinSystem kernel: [    4.368633] i915 0000:00:02.0: vgaarb: deactivate vga console
May 31 16:09:57 tsybinSystem kernel: [    4.369280] [drm] Supports vblank timestamp caching Rev 2 (21.10.2013).
May 31 16:09:57 tsybinSystem kernel: [    4.369281] [drm] Driver supports precise vblank timestamp query.
May 31 16:09:57 tsybinSystem kernel: [    4.369645] i915 0000:00:02.0: vgaarb: changed VGA decodes: olddecodes=io+mem,decodes=io+mem:owns=io+mem
May 31 16:09:57 tsybinSystem kernel: [    4.388466] [drm] Initialized i915 1.6.0 20190619 for 0000:00:02.0 on minor 0
May 31 16:09:57 tsybinSystem kernel: [    4.390198] ACPI: Video Device [GFX0] (multi-head: yes  rom: no  post: no)
May 31 16:09:57 tsybinSystem kernel: [    4.390271] input: Video Bus as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0A08:00/LNXVIDEO:00/input/input8
May 31 16:09:57 tsybinSystem kernel: [    4.420676] fbcon: i915drmfb (fb0) is primary device
May 31 16:09:57 tsybinSystem kernel: [    4.420712] Console: switching to colour frame buffer device 210x65
May 31 16:09:57 tsybinSystem kernel: [    4.420734] i915 0000:00:02.0: fb0: i915drmfb frame buffer device
May 31 16:09:57 tsybinSystem kernel: [    5.799949] [drm] Finished loading DMC firmware i915/kbl_dmc_ver1_04.bin (v1.4)
May 31 16:09:57 tsybinSystem kernel: [    5.808167] rtl8192ee: Using firmware rtlwifi/rtl8192eefw.bin
May 31 16:09:57 tsybinSystem kernel: [    5.810175] ieee80211 phy0: Selected rate control algorithm 'rtl_rc'
May 31 16:09:57 tsybinSystem kernel: [    5.810354] rtlwifi: rtlwifi: wireless switch is on
May 31 16:09:57 tsybinSystem kernel: [    6.311056] usbcore: registered new interface driver btusb
May 31 16:09:57 tsybinSystem kernel: [    6.359344] rtl8192ee 0000:01:00.0 wlp1s0: renamed from wlan0
May 31 16:09:57 tsybinSystem kernel: [    8.911569] snd_hda_intel 0000:00:1f.3: bound 0000:00:02.0 (ops i915_audio_component_bind_ops [i915])
May 31 16:09:57 tsybinSystem kernel: [   11.087017] snd_hda_codec_realtek hdaudioC0D0: autoconfig for ALC887-VD: line_outs=1 (0x14/0x0/0x0/0x0/0x0) type:line
May 31 16:09:57 tsybinSystem kernel: [   11.087018] snd_hda_codec_realtek hdaudioC0D0:    speaker_outs=0 (0x0/0x0/0x0/0x0/0x0)
May 31 16:09:57 tsybinSystem kernel: [   11.087019] snd_hda_codec_realtek hdaudioC0D0:    hp_outs=1 (0x1b/0x0/0x0/0x0/0x0)
May 31 16:09:57 tsybinSystem kernel: [   11.087020] snd_hda_codec_realtek hdaudioC0D0:    mono: mono_out=0x0
May 31 16:09:57 tsybinSystem kernel: [   11.087020] snd_hda_codec_realtek hdaudioC0D0:    inputs:
May 31 16:09:57 tsybinSystem kernel: [   11.087021] snd_hda_codec_realtek hdaudioC0D0:      Front Mic=0x19
May 31 16:09:57 tsybinSystem kernel: [   11.087022] snd_hda_codec_realtek hdaudioC0D0:      Rear Mic=0x18
May 31 16:09:57 tsybinSystem kernel: [   11.087023] snd_hda_codec_realtek hdaudioC0D0:      Line=0x1a
May 31 16:09:57 tsybinSystem kernel: [   11.220909] intel_rapl_common: Found RAPL domain package
May 31 16:09:57 tsybinSystem kernel: [   11.220910] intel_rapl_common: Found RAPL domain core
May 31 16:09:57 tsybinSystem kernel: [   11.220911] intel_rapl_common: Found RAPL domain uncore
May 31 16:09:57 tsybinSystem kernel: [   11.220911] intel_rapl_common: Found RAPL domain dram
May 31 16:09:57 tsybinSystem kernel: [   11.316609] input: HDA Intel PCH Front Mic as /devices/pci0000:00/0000:00:1f.3/sound/card0/input9
May 31 16:09:57 tsybinSystem kernel: [   11.316645] input: HDA Intel PCH Rear Mic as /devices/pci0000:00/0000:00:1f.3/sound/card0/input10
May 31 16:09:57 tsybinSystem kernel: [   11.316676] input: HDA Intel PCH Line as /devices/pci0000:00/0000:00:1f.3/sound/card0/input11
May 31 16:09:57 tsybinSystem kernel: [   11.316706] input: HDA Intel PCH Line Out as /devices/pci0000:00/0000:00:1f.3/sound/card0/input12
May 31 16:09:57 tsybinSystem kernel: [   11.316736] input: HDA Intel PCH Front Headphone as /devices/pci0000:00/0000:00:1f.3/sound/card0/input13
May 31 16:09:57 tsybinSystem kernel: [   11.316763] input: HDA Intel PCH HDMI/DP,pcm=3 as /devices/pci0000:00/0000:00:1f.3/sound/card0/input14
May 31 16:09:57 tsybinSystem kernel: [   11.316791] input: HDA Intel PCH HDMI/DP,pcm=7 as /devices/pci0000:00/0000:00:1f.3/sound/card0/input15
May 31 16:09:57 tsybinSystem kernel: [   11.316822] input: HDA Intel PCH HDMI/DP,pcm=8 as /devices/pci0000:00/0000:00:1f.3/sound/card0/input16
May 31 16:09:57 tsybinSystem kernel: [   18.296005] EXT4-fs (sda2): mounted filesystem with ordered data mode. Opts: (null)
May 31 16:09:57 tsybinSystem kernel: [   18.296114] EXT4-fs (sda3): mounted filesystem with ordered data mode. Opts: (null)
May 31 16:09:57 tsybinSystem kernel: [   18.352738] audit: type=1400 audit(1590930596.489:2): apparmor="STATUS" operation="profile_load" profile="unconfined" name="libreoffice-senddoc" pid=763 comm="apparmor_parser"
May 31 16:09:57 tsybinSystem kernel: [   18.363016] audit: type=1400 audit(1590930596.497:3): apparmor="STATUS" operation="profile_load" profile="unconfined" name="/usr/sbin/tcpdump" pid=764 comm="apparmor_parser"
May 31 16:09:57 tsybinSystem kernel: [   18.365265] audit: type=1400 audit(1590930596.501:4): apparmor="STATUS" operation="profile_load" profile="unconfined" name="/usr/bin/man" pid=771 comm="apparmor_parser"
May 31 16:09:57 tsybinSystem kernel: [   18.365267] audit: type=1400 audit(1590930596.501:5): apparmor="STATUS" operation="profile_load" profile="unconfined" name="man_filter" pid=771 comm="apparmor_parser"
May 31 16:09:57 tsybinSystem kernel: [   18.365268] audit: type=1400 audit(1590930596.501:6): apparmor="STATUS" operation="profile_load" profile="unconfined" name="man_groff" pid=771 comm="apparmor_parser"
May 31 16:09:57 tsybinSystem kernel: [   18.370132] audit: type=1400 audit(1590930596.505:7): apparmor="STATUS" operation="profile_load" profile="unconfined" name="system_tor" pid=765 comm="apparmor_parser"
May 31 16:09:57 tsybinSystem kernel: [   18.373775] audit: type=1400 audit(1590930596.509:8): apparmor="STATUS" operation="profile_load" profile="unconfined" name="/usr/sbin/ippusbxd" pid=772 comm="apparmor_parser"
May 31 16:09:57 tsybinSystem kernel: [   18.374398] audit: type=1400 audit(1590930596.509:9): apparmor="STATUS" operation="profile_load" profile="unconfined" name="libreoffice-xpdfimport" pid=774 comm="apparmor_parser"
May 31 16:09:57 tsybinSystem kernel: [   18.375565] audit: type=1400 audit(1590930596.509:10): apparmor="STATUS" operation="profile_load" profile="unconfined" name="/usr/lib/snapd/snap-confine" pid=773 comm="apparmor_parser"
May 31 16:09:57 tsybinSystem kernel: [   18.375567] audit: type=1400 audit(1590930596.509:11): apparmor="STATUS" operation="profile_load" profile="unconfined" name="/usr/lib/snapd/snap-confine//mount-namespace-capture-helper" pid=773 comm="apparmor_parser"
May 31 16:09:57 tsybinSystem kernel: [   19.113630] vboxdrv: Found 4 processor cores
May 31 16:09:57 tsybinSystem kernel: [   19.132178] vboxdrv: TSC mode is Invariant, tentative frequency 3599998972 Hz
May 31 16:09:57 tsybinSystem kernel: [   19.132178] vboxdrv: Successfully loaded version 6.1.6 (interface 0x002d0001)
May 31 16:09:57 tsybinSystem kernel: [   19.341420] VBoxNetFlt: Successfully started.
May 31 16:09:57 tsybinSystem kernel: [   19.349550] VBoxNetAdp: Successfully started.
May 31 16:09:57 tsybinSystem kernel: [   19.522079] Bluetooth: BNEP (Ethernet Emulation) ver 1.3
May 31 16:09:57 tsybinSystem kernel: [   19.522080] Bluetooth: BNEP filters: protocol multicast
May 31 16:09:57 tsybinSystem kernel: [   19.522082] Bluetooth: BNEP socket layer initialized
May 31 16:09:58 tsybinSystem kernel: [   20.285068] Generic Realtek PHY r8169-300:00: attached PHY driver [Generic Realtek PHY] (mii_bus:phy_addr=r8169-300:00, irq=IGNORE)
May 31 16:09:58 tsybinSystem kernel: [   20.397196] r8169 0000:03:00.0 enp3s0: Link is Down
May 31 16:10:00 tsybinSystem kernel: [   22.136462] Bluetooth: RFCOMM TTY layer initialized
May 31 16:10:00 tsybinSystem kernel: [   22.136467] Bluetooth: RFCOMM socket layer initialized
May 31 16:10:00 tsybinSystem kernel: [   22.136469] Bluetooth: RFCOMM ver 1.11
May 31 16:10:01 tsybinSystem kernel: [   23.019781] wlp1s0: authenticate with 60:a4:4c:8c:41:a8
May 31 16:10:01 tsybinSystem kernel: [   23.041106] wlp1s0: send auth to 60:a4:4c:8c:41:a8 (try 1/3)
May 31 16:10:01 tsybinSystem kernel: [   23.127844] wlp1s0: authenticated
May 31 16:10:01 tsybinSystem kernel: [   23.128036] wlp1s0: associate with 60:a4:4c:8c:41:a8 (try 1/3)
May 31 16:10:01 tsybinSystem kernel: [   23.230244] wlp1s0: RX AssocResp from 60:a4:4c:8c:41:a8 (capab=0x411 status=0 aid=2)
May 31 16:10:01 tsybinSystem kernel: [   23.240073] wlp1s0: associated
May 31 16:10:01 tsybinSystem kernel: [   23.615078] IPv6: ADDRCONF(NETDEV_CHANGE): wlp1s0: link becomes ready
May 31 16:10:13 tsybinSystem kernel: [   35.684396] rfkill: input handler disabled
