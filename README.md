# Malysis

Malysis is a static malware analyzer using PE files
## Installation



```bash
git clone https://github.com/subzero-sh/malysis.git
cd malysis
pip3 install -r requirements.txt
```

## Usage

```python
python3 malysis.py <folder>
```

# Feature extracted

- **Suspicious entropy** ratio
- **Suspicious name** ratio
- Suspicious **code size**
- Suspicious **debugging time-stamp** 
- Number of **export**
- Number of **anti-debugging** calls
- Number of **virtual-machine detection** calls
- Number of **suspicious API** calls
- Number of **suspicious strings**
- Number of **YARA** rules matches 
- Number of **URL** found
- Number of **IP** found
- **VirusTotal** database detection
- **Import hash**


