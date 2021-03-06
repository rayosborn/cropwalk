# cropwalk
This repository contains spreadsheets designed to be used by treasurers of CROP Hunger Walks. Both Excel and Apple Numbers versions are available for download.

![Screenshot](https://github.com/rayosborn/cropwalk/blob/master/cropwalk-spreadsheet.png)

General Use
===========
The files contain multiple worksheets that are linked to allow results from individual teams to be consolidated for overall summaries.
* The first worksheet is a setup page where you can enter the full names of the different teams in your walk. Each team has an abbreviation, set by default to “Team 1”, “Team 2”, *etc*. These are also the names of the worksheets containing the results for each team. You are welcome to change these abbreviations, but please make sure that you also change the relevant worksheet names to match them. 
* The second sheet is a summary sheet that should not be edited. It only contain numbers auto-filled in from other sheets.
* The third is an accounts sheet, where you can enter direct donations from businesses, *etc*, along with your expenses. The first column of the top table, labelled “Collections” should be auto-filled from the other sheets. It represents all the money that was counted in the walker envelopes or raised online. The second column, labelled “Processed”, is something you enter manually, as you balance the books. In the “Cash” row, for example, it can be used to enter the money when it is deposited in a local bank account, while the “Checks” row can be used to enter the sum of all the checks before sending them to CWS. Any money sent to CWS is added to the “Sent” column. At the end, all three columns (“Collected”, “Processed”, and “Sent”) should have the same totals. Also, the “Net Total” and “Sent to CWS” on the summary sheet should eventually match. However, the total that CWS reports that you have collected online won’t necessarily match the “Total Online” number in the summary sheet, because the latter does not include business or miscellaneous donations online, i.e., those not designated to a walker or team. You can see all the undesignated donations in the CWS summaries they will send you on request.
* There are separate worksheets for each team. When team captains sign out the envelopes, the team’s envelope numbers can be updated. If  the team captains send the names of those who have signed out each envelope, this information can be filled in before the walk to speed up counting. Online-only donations can be added as separate rows at the end. 
* The total cash and checks in each walker's envelopes should be added to their respective columns during the counting. The “Pledged” column is, by default, the sum of the "Cash", "Checks" and "Online" columns, but it can be changed manually if there is a shortfall in what the walker claimed to have submitted. This discrepancy will show up in the “Still Due” column until it is resolved. Team donations that are not in any envelopes, *e.g.*, if they are online, can be added on the bottom row.

Adding and Removing Teams
=========================
* To add a team, insert a row above the ‘Unaffiliated’ team on the Setup sheet. Duplicate one of the team sheets and edit the formula of the full name field to point to the full name in this table (In Excel, you may need to change the cell type to "General" to make sure the cell reference is interpreted as a formula). Make sure that the team abbreviation and sheet names match. Do the same on the “Summary” and “Accounts” sheets and copy the formulae from another team row. 
* To remove a team, delete the sheet and the corresponding rows here and in the “Summary” and “Accounts” sheets.

Envelope Numbers
================
* Church World Service is now encouraging the use of unnumbered donation envelopes to save printing costs. The envelope column now contains a formula giving the row number, but if numbered envelopes are used, the formulae can be replaced by their respective numbers.