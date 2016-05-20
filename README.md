# RDS-Channel

Simple and fast application without any runtime dependency (except libc) that copies all keys from one REDIS databse to another one with custom key prefix. After first copy it is monitoring all key changes and updates values

# Install from remotes

```bash
git clone git clone --recursive URL
make
make install
# or
make package
```

# Install from cloned remote

```bash
git submodule update --init --recursive
make 
make install
# or
make package
```

# Usage

Run `rds-channel` to see help, or use wizard `rds-add-channel` for install Supervisor config