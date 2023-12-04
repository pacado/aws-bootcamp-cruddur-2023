# Week 0 — Billing and Architecture


aws sns subscribe \
    --topic-arn arn:aws:sns:eu-west-3:341379542691:billing-alarm \
    --protocol email \
    --notification-endpoint lawrencemkjohny@gmail.com