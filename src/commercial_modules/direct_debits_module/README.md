# Direct Debits Module

The Sage 200 Direct Debits Module allows you to collect payments from your customers by direct debit using the Banks Automated Clearing Service (BACS).

Both the SL Account screen and the CB Account screen have been modified to allow customers and bank accounts to be marked as available for direct debit collection. New fields have been added to store all the information needed for collections, and the user has the ability to generate AUDDIS files (in generic format and BACS Standard 18 format).

Once accounts have been flagged and the required information populated, the user is then able to create and maintain ‘Batches’ of transactions within a new screen within Sage.

A filter screen has been added to allow users to quickly populate and select which transactions to include in the batch. The user can choose to amend the collection value (potentially splitting the amount to be collected for an invoice over multiple batches) as well as being able to include ad-hoc transactions should they require.

The Direct Debits Module will also allow users to automatically generate and send notification emails to all of the customers contained within a batch (these emails can be customised on request). If paper notifications are required, then collection letters can be produced for those customers who do not have an email address on their account.

When it comes to generating the actual output file, batches can be exported to a range of supported file formats, including BACS Standard 18 and SEPA for International Collections (further file formats can be created on request). Once a batch has been exported, physical transmission to BACS can be done via transmission software such as ALBANY, though in most cases the banks provide their own software to achieve this.

Finally, once a batch is ready for processing, the Direct Debits module will allow the user to post all of the transactions within a batch to the sales ledger, performing the receipting and allocation processes automatically.




Our Direct Debits Module also offers support for a range of plugins, should their use require further customisations than the base module provides. We offer a Scheduled Payments Plugin (detailed below), which will allow the user to schedule a payment or invoice to be collected over a range of dates.