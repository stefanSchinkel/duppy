Duppy
-----

Duppy is a simple script to find duplicate files in a given
directory and copies the unique ones to another dir. Comparisons
are done using the file's MD5hashes. It is an absolutely straight-forward,
brute-force, non-smart and class-less approach and I only used it to 
clean up my photo library.

Invoke with:
```bash
python duppy inputDir outputDir
```

Test files can be created using eg. ``dd if=/dev/random of=rand5.dat bs=100000 count=1`` which
generates a 100kb file with random data. For testing purposes files like these are in `in/` and `out/`
