# Invoice Chase

**Paste this URL into any AI chat and it runs. No install, no key.**

```
Read https://raw.githubusercontent.com/nradawg/invoice-chase/main/README.md and run it on me.
```

---


**Use this when** an invoice is late and you are about to write an email you
will regret, or you have been quietly not writing one for three weeks.

## The rule

> Check that the invoice is payable before you decide the client is a problem.
> Most late invoices are a mechanical failure wearing the costume of bad faith.

Wrong email, no purchase order number, a portal nobody told you about, terms the
client's system reads as net 60. Each one looks exactly like being ignored. If
you escalate into a mechanical failure you burn a good client, and the invoice
is still unpayable afterward.

## How it works

**1. I audit the invoice first, as a document.** Does it carry the reference AP
needs, the dates, the agreed terms, and a one click way to pay. A missing PO
number stops payment cold and nobody emails to say so.

**2. I compute the days past due from the real dates**, not from how long it
feels. It goes in the messages, because a day count cannot read as nagging.

**3. I read your agreement before writing any consequence.** A late fee you can
actually charge is one that was in the terms the client accepted before the
work. If it is not in there, I will not put it in the letter. A fee invented at
the chase stage is generally not collectible, and announcing one tells the
client you are improvising.

**4. I write three messages, escalating, each one shorter than the last.** They
go to different people on purpose.

## What you see

```
INVOICE CHASE: $3,200, client stopped replying

Q  What is the real due date and how late is it?
A  Invoiced Sep 12 on net 15, so due Sep 27. Today is Oct 19.
   22 days past due.
   CHECKED, arithmetic from the dates you gave.

Q  Did it go to someone who can pay it?
A  You sent it to your day to day contact.
   FROM YOU. This is the likeliest failure. A project contact is
   usually not accounts payable and often cannot pay anything.

Q  Does the invoice carry a PO or reference number?
A  No.
   FROM YOU, I read the invoice you pasted. If their process needs
   one, the invoice is currently unpayable and silence is the
   normal result.

Q  Can you charge a late fee?
A  No. The agreement you pasted has payment terms and no late fee
   or interest clause.
   CHECKED, and this is why message 3 below names a work stop and
   not a percentage.

Q  Is any work still being delivered on this account?
A  Yes, you are mid build.
   FROM YOU. That is your leverage and it is the only one you have
   that costs you nothing.

  5 answers. 0 guessed, 2 checked.
  Fix the PO question first, it may end this today.
```

Then the three messages.

## The three messages

**Now. To your contact. Assume a slip.**

```
Hi [name], invoice 104 for $3,200 was due Sep 27 and I do not see it
come through. Is there a PO number or an AP address it needs to go to?
Happy to resend it in whatever format works.
```

**Day 7. To your contact, copying accounts payable. Name the term.**

```
Hi [name], following up on invoice 104, $3,200, now 29 days past the
net 15 terms. Copying AP. Can one of you give me a date it will be paid?
```

**Day 14. To the person who approved the work, copying both. State what
happens.**

```
Hi [name], invoice 104 for $3,200 is 36 days past due and I have not
had a payment date. I am pausing work on [project] until it clears.
Send me a date and I will keep going.
```

Each is under four sentences, asks for a date rather than an apology, and never
says "just circling back." The escalation is who receives it, not the tone.

## Limits

**The trap.** A naive version opens with a late fee or interest charge that is
nowhere in your contract, because that is what chase templates do. It reads firm
and it is worse than useless, since an unagreed fee is usually not enforceable
and AP will route your invoice to a dispute queue instead of a payment run. The
same naive version escalates tone on day two without ever asking whether the
invoice reached anyone who can pay it.

Before you mention small claims court, look up your own state's limit and filing
process. Search your state name plus "small claims court limit" on a .gov site,
and do not name a court in an email until you have checked it is the right one.
If you want a late fee on future work, that clause goes in the next contract,
and many states cap interest on overdue amounts, so check your state's limit
before writing any number into an agreement.

This cannot make a client who has no money pay you. If their last three invoices
were also late, the real decision is whether to keep working for them, and this
does not make that one.

---

## How this one knows what it knows

Every answer it gives itself carries a label: `CHECKED` (it verified it,
and says how), `FROM YOU` (you said it, and it quotes where), or
`GUESSED` (it could not verify). Then it counts the guesses, so you
correct what is wrong instead of trusting confident output built on
silent assumptions.

> Never ask for something you can check.
> Never assume something you cannot check.

One of 48 skills. The rest, and the house rules: [https://github.com/nradawg/assume-nothing](https://github.com/nradawg/assume-nothing)

MIT.
