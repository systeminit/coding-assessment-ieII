# Integration Engineer II Take Home Assessment

This is the repository for the System Initiatives Integration Engineer II take-home assessment. It is designed to verify:

* That you have some proficiency with programming, specifically typescript
* That you can read code and adapt it to your needs
* That you have familiarity with the cloud, and can deploy infrastructure
* That you can ramp up on new technology quickly and communicate what you've learned.

We use a take-home assessment so that you can have your most productive environment at hand. I am personally here to help. I fully expect that you will reach out to me on Discord (username: keeb) for questions or assistance. This is natural and core to the way that we work at System Initiative.

Spend no more than 4 hours on this assessment.

## First

Get familiar with System Initiative. Sign up for an account, login, and join your workspace. There is a video that is presented that gives a tutorial of the product. Follow it.

If you do not have access to an AWS account: that is fine. Feel free to set your endpoint to `http://localstack.keeb.dev` in your AWS Credential. No other field needs to be filled out.

## Next

Create a new asset: `Doubler`

### The Doubler

1. Create a new change set `Change Set 1`
2. Click on the customize screen
3. Click on the `+` Create new Asset button, enter asset name `Doubler`
4. In the editor, create  2 attributes, 1 input
attribute and and another which contains the computed value. Also, make sure it has an
output socket which contains the computed value.
5. Change the category to `Doubler`
6. Click `Regenerate Asset`
7. Click the new function button and select attribute function. Set the output
   location to `/root/computed`
8. Add an input parameter `value` of type `string`
9. Click `Edit Bindings` and set the binding to `/root/domain/input`
10. Write a function that doubles the input value
11. Go back to the modeling screen and drag the new `Doubler` component onto the
    canvas
12. Enter a value in the `input` field to `8`
13. Notice that the `computed` field of the asset is now `16`

### Expand the Asset

Take what you have learned and add a new attribute to the component `tripled`, and create the associated attribute/binding to triple the asssets input.

## Presentation

Once you have completed the above and are ready to proceed, let us know. We will schedule a follow up presentation where we talk about your experience using System Initiative, look at the Doubler component you've built, and think about different ways to expand it.

