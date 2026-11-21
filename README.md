You pulled an M.2 SSD out of an old laptop and want to read it from a machine with only a regular SATA port. An M.2 NGFF to SATA adapter looks like a ten-minute fix, and it is, but only if the SSD speaks the right language.

The catch: M.2 doesn't automatically mean SATA

An M.2 NGFF-to-SATA adapter doesn't translate protocols. It passes a SATA signal through a different connector, so the drive has to be SATA to begin with. A SATA-only adapter will not turn a PCIe/NVMe SSD into a SATA drive. M.2 describes the card shape and connector, not the protocol.

Check before you buy

Protocol: look up the drive's exact model number and confirm it says SATA. If it says PCIe, NVMe or Gen3/Gen4 x4, a SATA-only adapter won't work.
Keying: B-key drives have one notch and B+M-key drives have two. Many SATA drives use B+M, but so do some two-lane NVMe drives, so keying alone doesn't prove the drive is SATA.
Length: 2230, 2242, 2260 or 2280 (width and length in mm). Make sure the adapter supports your size.
Direction: if the SSD goes into the product, it's an SSD adapter. If the product goes into an M.2 slot, it's a host expansion card that adds SATA ports, which is a different thing.

How to install it

Identify the SSD and match its protocol, key and length to the adapter's spec.
Power down and disconnect power. Touch grounded metal and hold the drive by its edges.
Insert the SSD at a slight angle, press it flat and secure it with the screw or latch. Never force a mismatched connector.
Close the enclosure if there is one.
Connect SATA data and power.
Check BIOS/UEFI and your disk utility. If the drive holds files you need, don't initialise or format it before backing up.

Will it be faster?

No. Speed is set by the SATA interface. SATA III tops out around 600 MB/s, and many SATA SSDs reach roughly 500–560 MB/s in sequential transfers, though that's a typical range, not a guarantee. If the host port is SATA II, the cap drops to about half.

Drive not detected?

Missing in BIOS: check protocol compatibility and reseat the connections.
In BIOS but not in File Explorer: look in Disk Management, and don't format a drive with data you need.
Intermittent: recheck the connector and power.
NVMe drive not working: you need an NVMe-capable interface or enclosure.

Full guide, with a compatibility table and adapter examples from Tripp Lite and StarTech.com: https://ssdguides.com/m-2-ngff-to-sata-adapter/
