# cuttlefish

**cuttlefish** is an outgrowth of my frustration with enumerating hosts with hard to find files/directories in CTF-style offensive security practice. Sometimes, enumerations that yielded success could reach timelines of up to 6.5+ hours with over 200,000 unique combinations of words to test. This becomes unfeasible or practically inefficient fairly rapidly, especially if using wordlists with permutations on common file names. This project aims to ease the pain of large-scale enumeration by using concurrent, distributed, enumeration through an automated network of AWS-hosted slaves.