# kywy-doc

## 1 Configure credentials

Create a file called `.env` in the kywy-doc folder.
The file should have the following content:

```bash
# Information to connect to KAWA
KAWA_API_URL=<THE URL OF THE KAWA INSTANCE>
KAWA_API_KEY=<YOUR API KEY>
KAWA_WORKSPACE=<THE WORKSPACE ID>
```

Here is an example:

```bash
KAWA_API_URL=https://wayne.kawa.ai
KAWA_API_KEY=dsf4wFsrstgrsRSGrssrrghrts
KAWA_WORKSPACE=1
```

In order to obtain a valid KAWA_API_KEY, 
please refer https://docs.kawa.ai/python-api-for-data-analytics#cc5a769295544645891e469c2c30ee81: Retrieve the API Key.

## 2 Install the kywy package

Run the following command in your venv of choice:

`pip install kywy`

You can then explore the content through jupyter-lab.


