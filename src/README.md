# autochem

- automatting classification and regression for smiles and gene expression.
- entire classification and regression. 
- parallel threaded auto classifier and regressor for smiles to gene expression 


# Compilation 

```
sudo apt-get update
sudo apt-get install -y libboost-dev
sudo apt-get install -y libboost-serialization-dev
export CXXFLAGS="-std=c++20"
export CARGO_ENCODED_RUSTFLAGS=""
cargo clean
cargo build
cargo build -vv

```

```
cargo build
```

```
    _              _              ____   _                        
    / \     _   _  | |_    ___    / ___| | |__     ___   _ __ ___  
   / _ \   | | | | | __|  / _ \  | |     | '_ \   / _ \ | '_ ` _ \ 
  / ___ \  | |_| | | |_  | (_) | | |___  | | | | |  __/ | | | | | |
 /_/   \_\  \__,_|  \__|  \___/   \____| |_| |_|  \___| |_| |_| |_|
                                                                   

Autochemical ML
       ************************************************
       Author Gaurav Sablok,
       Email: gsablok@proton.me
      ************************************************

Usage: autochem <COMMAND>

Commands:
  smile-classify   logistic classifier for Smiles
  smile-regressor  regressor on smiles
  help             Print this message or the help of the given subcommand(s)

Options:
  -h, --help     Print help
  -V, --version  Print version

```

