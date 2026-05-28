# markdown-alert-example

A small repository to illustrate a small problem with Markdown Preview for
Github Alerts

First, we have a warning that renders as expected:

> [!WARNING]
> If you put a blank line after the `[!WARNING]` tag, GitHub will render things
> just fine.

Next, we have a warning that does not render as expected:

> [!WARNING]
>
> If you do not put a blank line after the `[!WARNING]` tag, Markdown Preview
> for Github Alerts will not render things correctly.

## Tests for others

Note without folllowing blank:

> [!NOTE]
> This is a note

Note with following blank:

> [!NOTE]
>
> This is a note

Tip without following blank:

> [!TIP]
> This is a tip.

Tip with following blank:

> [!TIP]
>
> This is a tip.

Important without following blank:

> [!IMPORTANT]
> This is a important.

Important with following blank:

> [!IMPORTANT]
>
> This is important.

Caution without following blank:

> [!CAUTION]
> Be cautious.

Caution with following blank:

> [!CAUTION]
>
> Be cautious.
