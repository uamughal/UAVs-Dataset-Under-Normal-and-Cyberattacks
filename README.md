
# Cyber-Physical Dataset for UAVs Under Normal Operations and Cyberattacks

Unmanned aerial vehicles (UAVs) are being used for various applications, but the associated cyber risks are also increasing. Machine learning techniques have been successfully adopted to develop intrusion detection systems (IDSs). However, none of the existing works published the cyber or physical datasets that have been used to develop the IDS, which hinders further research in this field. Hence, we developed a testbed that includes a UAV, controller, and data collection tools, to launch cyber-attacks (de-authentication denial-of-service (DoS), replay, false data injection, and evil twin attacks) on the UAV and collect cyber and physical data under normal and attack conditions, and we make this dataset publicly available.

# Instructions
- One CSV file is uploaded including normal flights of UAVs and UAV flights subject to cyber-attacks. 
- The Physical dataset includes sixteen features and the Cyber dataset includes thirty-seven features. Details about these features are found in our publication.
- Four cyber-attacks are considered in this dataset, namely, de-authentication denial-of-service attacks, replay attacks, false data injection attacks, and evil twin attacks. 
- Details about the testbed equipment are found in our publication.

# Dataset Details

The dataset includes:

Benign:       ||  Cyber: 1--9426             | Physical: 9427--13717
              ||                             |
DoS Attack    ||  Cyber: 13718--25389        | Physical: 25390--26363 
              ||                             |
Replay Attack ||  Cyber: 26364--38370        | Physical: 38371--39344  
              ||                             | 
Evil Twin     ||  Cyber: 39345--45028        | Physical: 45029--50502
              ||                             |
FDI           ||  Cyber: 50503--53976        | Physical: 53977--54784

# Citing this work
If you are using our implementation, you are encouraged to cite [our paper](https://ieeexplore.ieee.org/abstract/document/10368002).
``` 

@article{hassler2023cyber,
  title={Cyber-Physical Intrusion Detection System for Unmanned Aerial Vehicles},
  author={Hassler, Samuel Chase and Mughal, Umair Ahmad and Ismail, Muhammad},
  journal={IEEE Transactions on Intelligent Transportation Systems},
  year={2023},
  publisher={IEEE}
}

``` 


