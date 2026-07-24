# Packet-based IoT Event Detection

This repository accompanies the paper **"Detecting Smart Home Device Activities Using Packet-Level Signatures From Encrypted Traffic."**

The work presents a packet-based signature generation and detection approach for identifying smart-home IoT device activities from encrypted network traffic. It uses packet lengths and directions, and relies on packet counts rather than fixed time windows.

This work is an improved version of **PINGPONG**, originally presented at the Network and Distributed System Security Symposium (NDSS 2020). See the [PINGPONG paper](https://www.ndss-symposium.org/ndss-paper/packet-level-signatures-for-smart-home-devices/) and its [original GitHub repository](https://github.com/uci-plrg/pingpong).

Our approach addresses PINGPONG's dependence on fixed time windows by using packet-count thresholds, making activity detection more resilient to network delays and traffic-rate fluctuations. It also supports devices with multiple event types.

This repository includes only the core implementation folders, located under `Projects`.

## Key Result

The proposed system achieved:

- **98-99% average recall**
- **98-100% average precision**

The approach was evaluated using four public datasets and an emulated dataset with varying network delays.

## Repository

Clone the repository:

```bash
git clone https://github.com/mohammad-shamim-ahsan/Packet-based-IoT-Event-Detection.git
cd Packet-based-IoT-Event-Detection
```

## Publication

Mohammad Shamim Ahsan, Md. Shariful Islam, Md. Shohrab Hossain, and Anupam Das, "Detecting Smart Home Device Activities Using Packet-Level Signatures From Encrypted Traffic," *IEEE Transactions on Dependable and Secure Computing*, vol. 22, no. 2, pp. 1070-1081, March/April 2025.

[Read the paper](https://doi.org/10.1109/TDSC.2024.3424299)

## Citation

If you use this work, please cite:

```bibtex
@article{ahsan2025detecting,
  author  = {Mohammad Shamim Ahsan and Md. Shariful Islam and Md. Shohrab Hossain and Anupam Das},
  title   = {Detecting Smart Home Device Activities Using Packet-Level Signatures From Encrypted Traffic},
  journal = {IEEE Transactions on Dependable and Secure Computing},
  volume  = {22},
  number  = {2},
  pages   = {1070--1081},
  year    = {2025},
  doi     = {10.1109/TDSC.2024.3424299}
}
```

## Authors

- Mohammad Shamim Ahsan
- Md. Shariful Islam
- Md. Shohrab Hossain
- Anupam Das

## License

No license is currently specified. Please contact the authors before reusing or redistributing the code.
