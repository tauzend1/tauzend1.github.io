
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.4.1/semantic.min.css" integrity="sha512-8bHTC73gkZ7rZ7vpqUQThUDhqcNFyYi2xgDgPDHc+GXVGHXq+xPjynxIopALmOPqzo9JZj0k6OqqewdGO3EsrQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="app.css">
    <title>FTOR Formatter</title>
</head>
<body>
    <div class="ui container">
        <div class="ui form">
            <div class="ui segment">
                <h2>Basic Information</h2>
                <h4 class="ui dividing header">Patrol Information</h4>
                <div class="field">
                    <label>Date and Phase</label>
                    <div class="three fields">
                        <div class="field">
                            <input type="text" name="date" placeholder="DD/MMM/YYYY">
                        </div>
                        <div class="field">
                            <input type="text" name="time" placeholder="HH:MM">
                        </div>
                        <div class="field">
                            <input type="text" name="phase" placeholder="Phase 1/2/3/4">
                        </div>
                    </div>
                </div>
                <h4 class="ui dividing header">Personnel Information</h4>
                <div class="field">
                    <label>Field Training Officer</label>
                    <div class="three fields">
                        <div class="field">
                            <input type="text" name="fto_first" placeholder="First Name">
                        </div>
                        <div class="field">
                            <input type="text" name="fto_last" placeholder="Last Name">
                        </div>
                        <div class="field">
                            <input type="text" name="fto_serial" placeholder="Employee Number">
                        </div>
                    </div>
                </div>
                <div class="field">
                    <label>Trainee</label>
                    <div class="three fields">
                        <div class="field">
                            <input type="text" name="trainee_first" placeholder="First Name">
                        </div>
                        <div class="field">
                            <input type="text" name="trainee_last" placeholder="Last Name">
                        </div>
                        <div class="field">
                            <input type="text" name="trainee_serial" placeholder="Employee Number">
                        </div>
                    </div>
                </div>
            </div>
            <div class="ui segment">
                <h2>Attitude</h2>
                <div class="inline fields">
                    <label for="field1" class="header">Acceptance of Feedback/Criticism:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field1" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field1" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field1" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field1" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field2" class="header">Attitude toward Police Work:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field2" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field2" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field2" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field2" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field3" class="header">Integrity/Ethics:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field3" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field3" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field3" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field3" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field4" class="header">Leadership:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field4" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field4" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field4" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field4" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
            </div>
            <div class="ui segment">
                <h2>Appearence</h2>
                <div class="inline fields">
                    <label for="field5" class="header">Appearence:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field5" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field5" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field5" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field5" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
            </div>
            <div class="ui segment">
                <h2>Relationships</h2>
                <div class="inline fields">
                    <label for="field2" class="header">With Citizens/Community:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field6" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field6" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field6" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field6" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field3" class="header">With other Agencies' Members:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field7" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field7" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field7" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field7" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
            </div>
            <div class="ui segment">
                <h2>Performance</h2>
                <div class="inline fields">
                    <label for="field2" class="header">Driving Skill: All Conditions:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field8" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field8" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field8" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field8" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field3" class="header">Report Writing: Grammar/Spelling/Neatness:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field9" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field9" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field9" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field9" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field3" class="header">Field Performance: Self-Initiated Field Activity:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field10" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field10" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field10" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field10" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field3" class="header">Field Performance: General Conditions:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field11" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field11" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field11" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field11" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field3" class="header">Officer Safety: General Conditions:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field12" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field12" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field12" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field12" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field3" class="header">Control of Conflict: General Conditions:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field13" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field13" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field13" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field13" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field3" class="header">Problem-solving Techniques/Decision-making:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field14" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field14" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field14" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field14" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field3" class="header">Radio Communications:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field15" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field15" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field15" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field15" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field3" class="header">Mobile Computer Terminal:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field16" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field16" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field16" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field16" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field3" class="header">Use of Map Book/GPS: Orientation/Response Time:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field17" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field17" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field17" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field17" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
            </div>
            <div class="ui segment">
                <h2>Knowledge</h2>
                <div class="inline fields">
                    <label for="field2" class="header">Department Policies and Procedures:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field18" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field18" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field18" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field18" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field2" class="header">Criminal Law:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field19" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field19" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field19" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field19" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field2" class="header">Criminal Procedure:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field20" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field20" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field20" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field20" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
            </div>
            <div class="ui segment">
                <h2>(( Roleplay ))</h2>
                <div class="inline fields">
                    <label for="field2" class="header">Roleplay Quality:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field21" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field21" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field21" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field21" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field2" class="header">Character Depth/Portrayal:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field22" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field22" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field22" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field22" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
                <div class="inline fields">
                    <label for="field2" class="header">Out-of-Character Demeanor:</label>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field23" checked="" value="N/O" tabindex="0" class="hidden">
                            <label>Not Observed</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field23" value="C" tabindex="0" class="hidden">
                            <label>Competent</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field23" value="S" tabindex="0" class="hidden">
                            <label>Superior</label>
                        </div>
                    </div>
                    <div class="field">
                        <div class="ui radio checkbox">
                            <input type="radio" name="field23" value="N/I" tabindex="0" class="hidden">
                            <label>Needs Improvement</label>
                        </div>
                    </div>
                </div>
            </div>
            <div class="ui segment">
                <h2>Patrol Details</h2>
                <div class="field">
                    <label>Most Satisfactory Performance</label>
                    <textarea id="positive" placeholder="Must include the behavior the trainee excelled in or showcased great practical understanding of."></textarea>
                </div>
                <div class="field">
                    <label>Least Satisfactory Performance</label>
                    <textarea id="negative" placeholder="Must include the behavior that the trainee lacked in or could improve (e.g. Trainee is unable to make an independent decision on his own) as well the exact event(s) referencing the behavior (e.g. Trainee initially did not respond to the backup call of the vehicle pursuit on the black Sultan, until he was nudged by me).

                    The most important part of the report, as this is the documentation for what the trainee and the FTO should focus on."></textarea>
                </div>
                <div class="field">
                    <label>Delivered Practical/Theoretical Knowledge</label>
                    <textarea id="documented" placeholder="Provide a detailed list of theoretical/practical material delivered to the trainee during the course of the patrol based on the FTP Curriculum. The manner in which the information was passed on shall also be detailed, i.e. demonstrated by FTO, explained by FTO or performed by Trainee."></textarea>
                </div>
            </div>
            <div class="ui segment">
                <h2>Generator</h2>
            <div class="field">
                <label>Output</label>
                <textarea id="output" readonly></textarea>
            </div>
            <div class="ui secondary button" id="submit">Submit</div>
            <div class="ui primary button" id="copy">Copy to Clipboard</div>
        </div>
        </div>
    </div>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.4.1/semantic.min.js" integrity="sha512-dqw6X88iGgZlTsONxZK9ePmJEFrmHwpuMrsUChjAw1mRUhUITE5QU9pkcSox+ynfLhL15Sv2al5A0LVyDCmtUw==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script src="app.js"></script>
</body>
</html>
