# peopoly-magneto-x-bambu-studio
Peopoly Magneto X profiles for Bambu Studio

# Installation
The following commands assume that you have Bambu Studio installed to "C:\Program Files\Bambu Studio"

```
cd "C:\Program Files\Bambu Studio\resources"
git clone -n --depth=1 --filter=tree:0 https://github.com/mitant/peopoly-magneto-x-bambu-studio.git "C:\Program Files\Bambu Studio\resources\temp"
mv temp/.git ./.git
rm -rf temp
git sparse-checkout set --no-cone profiles
git checkout
```