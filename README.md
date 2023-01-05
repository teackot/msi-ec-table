# EC addresses and values table

! means confirmed on my laptop

| parameter               | MSI GF75 Thin 9SC | MSI Modern 15 A11M     | MSI Summit E16 Flip Evo A12MT | MSI Prestige 14 A10SC |
|-------------------------|-------------------|------------------------|-------------------------------|-----------------------|
| FW version              | 17F2EMS1.106      | 1552EMS1.118           | 1592EMS1.111                  | 14C1EMS1.101          |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| webcam address          | 0x2e              | 0x2e                   | 0x2e                          | 0x2e !                |
| cam hard address        | 0x2f              | 0x2f                   | ?                             | ?                     |
| webcam on               | 0x4a (bit1)       | bit1                   |                               | bit1 !                |
| webcam off              | 0x48 (bit1)       | bit1                   |                               | bit1 !                |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| Fn/Win address          | 0xbf              | 0xe8                   | 0xe8                          | 0xbf !                |
| Fn/Win                  | 0x40 (bit4 <- 0)  | bit4 <- 1              |                               | bit4 <- 0 !           |
| Win/Fn                  | 0x50 (bit4 <- 1)  | bit4 <- 0              |                               | bit4 <- 1 !           |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| battery mode address    | 0xef              | 0xd7                   | 0xef or 0xd7                  | 0xef !                |
| max                     | 0xe4              | 0xe4                   |                               | 0xe4 !                |
| balanced                | 0xd0              | 0xd0                   |                               | 0xd0 !                |
| min                     | 0xbc              | 0xbc                   |                               | 0xbc !                |
| super bat. mode address | n/a ?             | n/a ?                  | 0xeb                          | n/a ?                 |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| battery charge address  | n/a ?             | n/a ?                  | 0x42                          | 0x42                  |
| charging status address | n/a ?             | n/a ?                  | 0x31                          | 0x31                  |
| not charging            | n/a ?             | n/a ?                  | 0x01                          | 0x01                  |
| charging                | n/a ?             | n/a ?                  | 0x03                          | 0x03                  |
| discharging             | n/a ?             | n/a ?                  | 0x05                          | 0x05                  |
| full                    | n/a ?             | n/a ?                  | 0x09                          | 0x09                  |
| full, no power          | n/a ?             | n/a ?                  | 0x0d                          | 0x0d                  |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| power address           | n/a ?             | 0x30                   | n/a ?                         | n/a ?                 |
| PW lid open             | n/a ?             | bit1                   | n/a ?                         | n/a ?                 |
| PW AC connected         | n/a ?             | bit0                   | n/a ?                         | n/a ?                 |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| cooler boost address    | 0x98              | 0x98                   | 0x98                          | 0x98 !                |
| CB on                   | 0x82              | bit7 <- 1              |                               | bit7 <- 1 !           |
| CB off                  | 0x02              | bit7 <- 0              |                               | bit7 <- 0 !           |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| shift mode address      | 0xf2              | 0xf2                   | 0xd2                          | 0xf2                  |
| SM turbo                | 0xc4              | n/a                    |                               | ?                     |
| SM overclock            | n/a               | 0xc0                   | SM 0: 0xc0                    | ?                     |
| SM sport                | 0xc0              | n/a                    |                               | ?                     |
| SM balanced             | n/a               | 0xc1                   | SM 1: 0xc1                    | ?                     |
| SM comfort              | 0xc1              | n/a                    |                               | ?                     |
| SM eco                  | 0xc2              | 0xc2                   | SM 2: 0xc2                    | 0xc2                  |
| SM off                  | 0x80              | 0x80                   | SM off: ?                     | 0x80                  |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| FW version address      | 0xa0              | 0xa0                   | 0xa0                          | 0xa0 !                |
| FW version length       | 12                | 12                     | 12                            | 12   !                |
| FW date address         | 0xac              | 0xac                   | 0xac                          | 0xac !                |
| FW date length          | 8                 | 8                      | 8                             | 8    !                |
| FW time address         | 0xb4              | 0xb4                   | 0xb4                          | 0xb4 !                |
| FW time length          | 8                 | 8                      | 8                             | 8    !                |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| charge control address  | 0xef              |                        |                               |                       |
| CC offset start         | 0x8a              |                        |                               |                       |
| CC offset end           | 0x80              |                        |                               |                       |
| CC range min            | 0x8a              |                        |                               |                       |
| CC range max            | 0xe4              |                        |                               |                       |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| CPU (realtime, basic)   |                   |                        |                               |                       |
| RT temp address         | 0x68              | 0x68                   | 0x68                          |                       |
| RT fan speed address    | 0x71              | 0x71                   | 0xc9 or 0xcd (?)              |                       |
| RT fan speed base min   | 0x19              | 0x19                   |                               |                       |
| RT fan speed base max   | 0x37              | 0x37                   |                               |                       |
| BS fan speed address    | 0x89              | n/a                    | 0xcb (?)                      |                       |
| BS fan speed base min   | 0x00              | n/a                    |                               |                       |
| BS fan speed base max   | 0x0f              | n/a                    |                               |                       |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| GPU (realtime, basic)   |                   |                        |                               |                       |
| RT temp address         | 0x80              | 0x80                   | 0x80                          |                       |
| RT fan speed address    | 0x89              | 0x89                   | 0xcb (?)                      |                       |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| fan mode address        | 0xf4              | 0xd4                   | 0xd4 or 0xf4                  | 0xd4 or 0xf4          |
| FM auto                 | 0x0d              | n/a ?                  | 0x0d                          | probably same         |
| FM silent               | n/a ?             | 0x1d? (bit4)           | 0x1d                          | probably same         |
| FM basic                | 0x4d (bit6 ?)     | 0x4d? (bit6), unused   | 0x4d                          | probably same         |
| FM advanced             | 0x8d              | 0x8d? (bit7)           | 0x8d                          | probably same         |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| LED                     |                   |                        |                               |                       |
| LED mic mute address    | 0x2b              | 0x2c                   |                               | 0x2b !                |
| LED mute address        | 0x2c              | 0x2d                   |                               | 0x2c !                |
| LED state mask          | 0x4               | mute/micmute bit: bit1 |                               |                       |
| LED state off           | 0x80 (bit2)       | bit1                   |                               | bit2 !                |
| LED state on            | 0x84 (bit2)       | bit1                   |                               | bit2 !                |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| keyboard backlight      |                   |                        |                               |                       |
| BL mode address         | n/a ?             | n/a ?                  | 0x2c                          | n/a ?                 |
| BL mode always on       | n/a ?             | n/a ?                  | 0x00                          | n/a ?                 |
| BL mode auto turn off   | n/a ?             | n/a ?                  | 0x08                          | n/a ?                 |
| BL address              | 0xf3              | 0xd3                   | 0xd3                          | 0xf3 !                |
| BL state mask           | 0x3               | 0x3                    | 0x3                           | 0x3  !                |
| BL state off            | 0x80              | 0x80                   | 0x80                          | 0x80 !                |
| BL state on             | 0x81              | 0x81                   | 0x81                          | 0x81 !                |
| BL state half           | 0x82              | 0x82                   | 0x82                          | 0x82 !                |
| BL state full           | 0x83              | 0x83                   | 0x83                          | 0x83 !                |
|                         |                   |                        |                               |                       |
|                         |                   |                        |                               |                       |
| usb power share address | n/a ?             | n/a ?                  | 0xbf                          | n/a ?                 |
| USB PS off              | n/a ?             | n/a ?                  | 0x08                          | n/a ?                 |
| USB PS on               | n/a ?             | n/a ?                  | 0x28                          | n/a ?                 |

# sources list:

- MSI GF75 Thin 9SC (17F2EMS1.106) - msi-ec by BeardOverflow, [constants.h](https://github.com/BeardOverflow/msi-ec/blob/82adb09ea0d442670916ab7d3a13e51a9f6a3545/constants.h)
- MSI Modern 15 A11M (1552EMS1.118) - msi-ec-modern by ThePBone, [constants.h](https://github.com/ThePBone/msi-ec-modern/blob/70ce2d857148fbb0fc6e96bfb7fa8df261373d07/constants.h)
- MSI Summit E16 Flip Evo A12MT (1592EMS1.111) - MControlCenter by dmitry-s93, [operate.cpp](https://github.com/dmitry-s93/MControlCenter/blob/538f90573392717247e2f18c15b2e57509bcfbbc/src/operate.cpp)
- MSI Prestige 14 A10SC (14C1EMS1.101) - my laptop