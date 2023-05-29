# OGLAD_LAGUI_2_0
Off-Grid Load Analyzer Device - Load Analyzer GUI 2.0
To learn about how to use LAGUI 2.0 refer to the User_Manual in the resources folder.


#This is the LAGUI 2.0, created by ECE 23.3 at Seattle University. Members include Adrian Rivera, My Loan Tran, Caleb Malaer, and Brian Phuong.

#The dated folder is the current, and latest version of the Visual Studio Solution, its names must be updated after every version.

#Furthermore, within the Visual Studio Solution, there is some fixes that must be implemented in order to run the code within Visual Studio.
 	1. Form1.resx, Form2.resx, and Form3.resx found [F:\**\230529\230519\WIP\OGLAD_UI] needs to have their properties unblocked or else
		the code will not build.
	2. In order to run the program in Visual Studio you must first change the following lines of code:
		a. Library.cs: 30-31 88-89 -> instead of the true path of the devicelibrary.csv you must use the "Resources" one without
			the true path. It must be changed back to run the code after building and attempting to use the MSI.
		b. Form1.cs: 707-708. Follows the same principle of Library.cs above.
	3. To find the MSI and run the installer it can be found in: [F:\Documents\230529\230519\WIP\LAGUI_Installer\Debug] and will be updated
		after every build. To run the application after installing the MSI, user must run the application as Administrator.
	

#Thank You

Any questions or suggestions contact at: adrian.rivera.lv@gmail.com -> with subject LAGUI #.# ECE #.# or with LAGUI #.# Community Build


