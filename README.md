## GPU Monitoring

A GPU monitoring script to watch GPU status and their placement in Motherboard

GPUThe script is depend on the "dmidecode" information. If the information is not provide by the BIOS, then it cannot find which GPU in which PCI slot.

Since the script is accessing a lot of file that use root permission, it must be run using "sudo" 

Currently only support AMD GPU only. NVIDIA will be done in the future.

## Requirement

None

## Install

Not required

## Usage

To monitor GPU

```bash
sudo watch -n 2 ./gpumon
```

Other options are

```
-pci		: monitor by pci (default)
-gpu		: monitor by gpu
-csv		: output as csv
-sortbus	: sort by bus
```

## Donate
Donation are welcome 

BTC - bc1qur8aeernt2s7982sffyz7yv6882vgewsqdkyjg ( Segwit )  
BTC - 3Kcs5hWVQRUGtJKv3DjKbkzbGTEtFEQkUx ( Compatible )  
ETH - 0x9beb9B182a273Da689b08228385137440fEb8D6B  