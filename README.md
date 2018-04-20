# IST-597-Final-Project-Robert-Zuchowski
Building a random forest classifier of educational homogamy in the Panel Study of Income Dynamics

This project uses data from the Panel Study of Income Dynamics (PSID). The PSID is a longitudinal study used by researchers from many backgrounds interested in social, economic, and demographic proceesses. It is an ongoing survey that began with a first round in 1968 and has followed these members and their decendents.
The data for this excercise is downloaded from the main family file for 2015 found here: https://simba.isr.umich.edu/Zips/ZipMain.aspx
## Cleaning data

def imports(psid):
	#reads data from stata to df
	psid = pd.io.stata.read_stata('FAM2015ER.dta')
	return psid


