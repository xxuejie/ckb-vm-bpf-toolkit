# ckb-vm-bpf-toolkit

A toolkit for inspecting CKB-VM smart contracts powered by ebpf.

## Usage

Right now this is only tested on Ubuntu 22.04 machine.

Install [bcc](https://github.com/iovisor/bcc) and [python3-pyelftools](https://packages.ubuntu.com/jammy/python3-pyelftools) first(or you can install latest pyefltools via pip).

Note this requires a specific feature that is still a [PR](https://github.com/nervosnetwork/ckb-standalone-debugger/pull/62) at ckb-debugger side. For now you will need to manually compile ckb-debugger that contains the new probe mode.

Now one can navigate through individual tools in `tools` folder to try out different tools.
